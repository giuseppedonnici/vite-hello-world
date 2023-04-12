<script>
export default {
    name: "AppTitle",
    data() {
        return {
            title: "La mia prima app con Vite!"
        }
    }
}
</script>

<template>
    <h1>{{ title }}</h1>
</template>

<style>
    h1 {
        font-size: 2rem;
        position: absolute;
        left: 50%;
        transform: translateX(-50%);
        color: whitesmoke;
    }
</style>