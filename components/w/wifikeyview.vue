<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z06-kcsvy"/><path class="t40qbpwye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wifikeyview" /></template>
<style>
.t40qbpwye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.1 20.24l4.27-5.57a31.41 31.41 0 0 0-38.87.44L24.22 39.6l5.21-6.77");
}

.z06-kcsvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.1 29.72h-.64v-2.08a3.76 3.76 0 1 0-7.52 0v2.08h-.64a1.41 1.41 0 0 0-1.4 1.41v7.32a1.4 1.4 0 0 0 1.4 1.4h8.78a1.41 1.41 0 0 0 1.42-1.4h0v-7.32a1.42 1.42 0 0 0-1.4-1.41m-8.16 0h7.52");
}

</style>
