<script setup>
import Nav from "./components/layout/Nav.vue";
</script>

<template>
  <header>
    <Nav />
  </header>

  <main>
    <div class="container-fluid px-0">
      <RouterView />
    </div>
  </main>
</template>

<style scoped>
header {
  border: 1px solid #e5e7eb;
  height: 75px;
  align-items: center;
  padding-top: 5px;
}
</style>
