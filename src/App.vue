<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Nav from "./components/Nav.vue";
//import Index from "./pages/index.vue";
</script>

<template>
<Nav /> 
  <div class="container mx-auto">
    <router-view />
   
  </div>
</template>

