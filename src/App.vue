<template>
  <v-app>
    <header>
      <div class="wrapper"></div>
    </header>
    <nav>
      <v-app-bar class="d-flex justify-center" :elevation="8">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </v-app-bar>
    </nav>

    <div class="mt-16">
      <RouterView />
    </div>
  </v-app>
</template>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<style scoped></style>
