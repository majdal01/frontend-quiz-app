<script setup lang="ts">
import HomePage from './pages/HomePage.vue'
</script>

<template>
  <main>
    <HomePage />
  </main>
</template>


/*
1. Browser åbner index.html
   ↓
2. index.html siger: "Kør ./src/main.ts"
   ↓
3. main.ts siger: "Lav en Vue-app fra App.vue komponent"
   ↓
4. main.ts siger: "Sæt Vue-appen ind i div id="app" div
   ↓
5. Nu er din App.vue aktiv, og den renderes
*/