<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9eekdk1h"/><path class="lz1kgkz2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tachiyomisy" /></template>
<style>
.i9eekdk1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.576 34.543a8.81 8.81 0 0 0 7.391 3.326h4.435a7.413 7.413 0 0 0 7.392-7.392a7.413 7.413 0 0 0-7.392-7.391h-4.804a7.413 7.413 0 0 1-7.391-7.391a7.413 7.413 0 0 1 7.39-7.392h4.436c3.326 0 5.543.74 7.39 3.326");
}

.lz1kgkz2d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.919 4.5L24.244 24L11.081 4.5m13.163 39V24");
}

</style>
