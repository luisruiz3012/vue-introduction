<template>
    <div class="">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt, excepturi illum dignissimos velit suscipit, aspernatur dolor, ipsa nostrum alias iusto beatae reiciendis ducimus officiis dolores repudiandae repellendus at recusandae natus!</p>
        <p>{{text}}</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            text: "Hola vue",
        }
    }
}
</script>

<style scoped>
    p {
        color: red;
    }
</style>