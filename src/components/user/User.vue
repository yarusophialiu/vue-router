<template>
    <div>
        <h1>The User Page</h1>
        <hr>
        <button @click="navigateToHome" class="btn btn-primary">Go To Home</button>
        <router-view></router-view>
    </div>
</template>

<script>
export default {
    data() {
        return {
        }
    },
    watch: {
    },
    methods: {
        navigateToHome() {
            this.$router.push({ name: 'home' })
        }
    }
}
</script>>