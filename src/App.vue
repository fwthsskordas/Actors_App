<script setup>
import BreakingBadCards from './components/BreakingBadCards.vue';
</script>

<template>
<main>
  <Suspense>
    <template #default>
      <BreakingBadCards/>
    </template>
    <template #fallback>
      <div>
        <p>Loading...</p>
      </div>
    </template>
  </Suspense>
</main>
</template>

<style scoped>

</style>

