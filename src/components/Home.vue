<script setup>
import {authStore} from '../store/store';
</script>
<template >
    <div class="home">
    <h1 class="text-2xl mb-3">This is home page</h1>
    <p >
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aliquam eos cumque eligendi, doloribus quia eaque voluptatem? Maiores ullam ad deserunt est, facilis eligendi? Provident esse nostrum ea fugiat aliquid in nobis qui nesciunt asperiores voluptatibus expedita minima, eius iste consectetur sint similique delectus quibusdam blanditiis! Dignissimos voluptates voluptas magnam! Animi odio soluta fugiat! Impedit exercitationem, rerum esse, doloremque sint quia hic quae cupiditate asperiores a nesciunt autem reiciendis ipsum obcaecati neque, magnam minima tempore soluta pariatur! Id fugit perspiciatis tenetur dolore odit quam quasi veniam obcaecati minima consequatur, est pariatur? Inventore neque esse ipsum ullam, quos totam nihil? Quo eius suscipit incidunt maiores eveniet repudiandae laboriosam, eaque quae voluptates vel ab aspernatur libero mollitia delectus corporis, dicta tenetur quisquam sint, dolores cum expedita. Suscipit earum maiores, quibusdam dignissimos placeat eaque nobis facilis quisquam, tenetur aspernatur minima! Id rem impedit quos magnam quo accusantium, vel recusandae maiores omnis tempora sed ut ad delectus veritatis quisquam minima natus? Earum exercitationem pariatur iusto commodi praesentium non voluptatum voluptatibus fugit, iste enim rem consequuntur consequatur obcaecati, animi odit. Earum officia corporis modi error beatae, deserunt non inventore accusantium unde omnis eligendi. Ratione facere quas modi alias excepturi reiciendis, sequi vel voluptatibus qui dolorem asperiores!
    </p>

    <p class="text-2xl mt-10" v-if="authStore.isAuthenticated">
        This is some secret content
    </p>
</div>
    
</template>

<style scoped>

.home{
    background-color: aliceblue;
    height: 100%;
    width: 100%;

}
h1{
    background-color: darkgray;
    padding: 1rem;
    text-align: center;
}
p{
    padding: 1rem;
}
</style>
