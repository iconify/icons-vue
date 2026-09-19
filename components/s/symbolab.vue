<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="kyqju1biu"/><path class="m-lck__ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:symbolab" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.kyqju1biu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36 25.38v5.732a4.246 4.246 0 0 1-4.246 4.246h0a4.23 4.23 0 0 1-3.003-1.243");
}

.m-lck__ya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36 18.374v7.006a4.246 4.246 0 0 1-4.246 4.246h0a4.246 4.246 0 0 1-4.246-4.246v-7.006m-15.172 9.391c1.042 1.356 2.348 1.861 4.165 1.861h2.514a4.24 4.24 0 0 0 4.237-4.246h0a4.24 4.24 0 0 0-4.237-4.246h-2.778A4.24 4.24 0 0 1 12 16.888h0a4.24 4.24 0 0 1 4.237-4.247h2.514c1.817 0 3.123.505 4.165 1.861");
}

</style>
