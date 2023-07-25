<script setup>
import Navbar from './components/Navbar.vue';
</script>

<template>
  <div id="app">
    <header>
      <div class="container">

        <Navbar />
      </div>
    </header>

    <router-view />
  </div>
</template>

<style></style>
