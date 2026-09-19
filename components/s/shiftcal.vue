<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="mys8i0b6h"/><path class="m7im2crff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shiftcal" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.m7im2crff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.36 16.518h5.16v5.16H9.36zm0 7.997h5.16v5.16H9.36zm0 7.997h5.16v5.16H9.36zm24.12-15.994h5.16v5.16h-5.16zm0 7.997h5.16v5.16h-5.16zm0 7.997h5.16v5.16h-5.16zm-8.04-15.994h5.16v5.16h-5.16zm0 7.997h5.16v5.16h-5.16zm0 7.997h5.16v5.16h-5.16zM17.4 16.518h5.16v5.16H17.4zm0 7.997h5.16v5.16H17.4zm0 7.997h5.16v5.16H17.4z");
}

.mys8i0b6h {
  fill: none;
  stroke: currentColor;
  d: path("M5.5 13.136h37");
}

</style>
