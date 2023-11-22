<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
 <div id="nav">
 <router-lick style=padding: 5px;" to="/">Inicio</router-lick> |
  <router-lick style=padding: 5px;" to="/">Acerca de</router-lick>
</div>
  <div class="container">

  <RouterView />
  </div>
</template>

<style scoped>

</style>
