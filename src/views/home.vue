<template>
    <div class="home-container">
        <h1>VUE3教学</h1>
        <hr>
        <Mobanyvfa></Mobanyvfa>
        <Shuxingbangding></Shuxingbangding>
        <Tiaojianxuanran></Tiaojianxuanran>
    </div>
</template>

<script>
import Mobanyvfa from '../components/mobanyvfa.vue';
import Mobanyufa from '../components/mobanyvfa.vue';
import Shuxingbangding from '../components/shuxingbangding.vue';
import Tiaojianxuanran from '../components/tiaojianxuanran.vue';

export default {
    name: 'Home',
    components: {
        Mobanyvfa,
        Shuxingbangding,
        Tiaojianxuanran
    },

}
</script>

<style scoped>
.home-container{
    position: relative;
    z-index: 10;
}
h1{
    z-index: 11;
    color: aqua;
}
</style>