<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped lang="scss">
@font-face {
  font-family: 'Roboto';
  src:
    local('Roboto'),
    url(./fonts/Roboto/Roboto-Regular.ttf) format('truetype');
}
</style>
