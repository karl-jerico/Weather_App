<template>
  <div class="min-h-screen font-Roboto bg-weather-primary">
    <Navigation />
    <RouterView />
  </div>
</template>

<script setup lang="ts">
import { RouterView } from "vue-router";
import Navigation from "./components/Navigation.vue";
</script>
