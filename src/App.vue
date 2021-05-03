<template>
    <v-app>
        <app-navigation></app-navigation>
        <home-hero></home-hero>
<home-details></home-details>
<home-plans></home-plans>
        <v-content transition="slide-x-transition">
            <router-view></router-view>
        </v-content>
    </v-app>
</template>

<script>
import AppNavigation from '@/components/AppNavigation';
import HomeHero from './components/HomeHero.vue';
import HomeDetails from './components/HomeDetails.vue';
import HomePlans from './components/HomePlans.vue';


export default {
    name: 'App',
    components: {
        AppNavigation,
        HomeHero,
        HomeDetails,
        HomePlans
    }
};
</script>

<style>
</style>
