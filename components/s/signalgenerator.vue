<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="so_vpbysx"/><path class="r_u8aub-h"/></g><path class="mbf7uz_bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:signalgenerator" /></template>
<style>
.mbf7uz_bz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24v-4h4.9v8.19h4.85V24m0 0v-4h4.9v8.19H24V24m0 0v-4h4.9v8.19h4.85V24m0 0v-4h4.9v8.19h4.85V24M9.68 39.08L19.13 31v8.1m0-.02L28.58 31v8.1m0-.02L38 31v8.1m0-.02l5.44-4.67m-38.94 1L9.68 31v8.1");
}

.r_u8aub-h {
  d: path("M43.5 13.09c-.31.87-.63 1.73-1 2.44a5.6 5.6 0 0 1-.78 1.39a.79.79 0 0 1-1.42 0a5.6 5.6 0 0 1-.78-1.39c-.32-.71-.64-1.57-1-2.44s-.63-1.72-.95-2.43a6 6 0 0 0-.78-1.39a.79.79 0 0 0-1.42 0a5.6 5.6 0 0 0-.78 1.39c-.32.71-.64 1.57-.95 2.43s-.63 1.73-1 2.44a6.4 6.4 0 0 1-.64 1.39a.79.79 0 0 1-1.42 0a5.6 5.6 0 0 1-.78-1.39c-.32-.71-.64-1.57-.95-2.44s-.63-1.72-.95-2.43a6.4 6.4 0 0 0-.78-1.39a.79.79 0 0 0-1.42 0a5.6 5.6 0 0 0-.78 1.39c-.32.71-.64 1.57-.95 2.43c-.14.38-.27.75-.41 1.11");
}

.so_vpbysx {
  d: path("M24.43 11.87c-.14.36-.27.73-.41 1.1c-.31.86-.63 1.72-.95 2.44a5.8 5.8 0 0 1-.78 1.39a1 1 0 0 1-.71.44a1 1 0 0 1-.71-.44a6.6 6.6 0 0 1-.78-1.39c-.32-.72-.64-1.58-.95-2.44s-.63-1.72-.95-2.44a5.8 5.8 0 0 0-.78-1.39a1 1 0 0 0-.71-.43a1 1 0 0 0-.71.43a6.6 6.6 0 0 0-.78 1.39c-.32.72-.64 1.58-1 2.44s-.63 1.72-.95 2.44a5.8 5.8 0 0 1-.78 1.39a1 1 0 0 1-.71.43a1 1 0 0 1-.71-.43a6.2 6.2 0 0 1-.78-1.39c-.32-.72-.64-1.58-.95-2.44s-.63-1.72-1-2.44a5.8 5.8 0 0 0-.78-1.39a1 1 0 0 0-.71-.43a1 1 0 0 0-.71.43a5.8 5.8 0 0 0-.78 1.39c-.32.72-.64 1.58-1 2.44");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
