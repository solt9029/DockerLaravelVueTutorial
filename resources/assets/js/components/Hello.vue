<template>
    <div>
        <span class="name">{{name}} !!</span>
    </div>
</template>

<script>
    export default {
        props: ['name'],
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
