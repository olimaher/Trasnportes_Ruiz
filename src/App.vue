<script setup>
import { RouterLink, RouterView } from 'vue-router'
import MenuPrincipal from './components/MenuPrincipal.vue';
import Logo from './components/Logo.vue';
</script>

<template>
 <Header class="d-flex align-items-center">
  <Logo></Logo>
  <MenuPrincipal></MenuPrincipal>
</Header>
</template>

<style scoped>

</style>
