<template>
  <div class="avatar placeholder">
    <div class="bg-neutral-focus text-neutral-content rounded-full w-16">
      <span class="text-xl">{{ user.first_name }}</span>
    </div>
  </div>
  <div class="offer">
    <span> {{ user.first_name }} {{ user.last_name }} </span>
    <p class="text-gray-500">
      {{ user.email }}
    </p>
  </div>
</template>
<script setup>
const props = defineProps({
  user: Object,
});
</script>
<style lang=""></style>