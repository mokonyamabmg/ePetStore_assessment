<template>
<div>
    <the-header></the-header>
    <router-view>
    </router-view>
</div>
</template>

<script>
import TheHeader from './layouts/TheHeader.vue';

export default {
    components: {
        TheHeader
    },
    data() {
        return {
        }
    },
    created() {

    }
}
</script>

<style scoped>

</style>
