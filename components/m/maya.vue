<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="qfr2c6nvk"/><path class="m92ymffle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:maya" /></template>
<style>
.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.m92ymffle {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.722 21.581v3.646a2.21 2.21 0 0 1-4.419 0V21.58M9.5 23.79a2.21 2.21 0 0 1 4.419 0v3.646M9.5 21.581v5.855m4.419-3.646a2.21 2.21 0 0 1 4.419 0v3.646m6.695-2.209a2.21 2.21 0 0 1-4.419 0V23.79a2.21 2.21 0 1 1 4.419 0m0 3.646v-5.855M38.5 25.227a2.21 2.21 0 0 1-4.419 0V23.79a2.21 2.21 0 1 1 4.419 0m0 3.646v-5.855");
}

.qfr2c6nvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.722 25.227v2.982a2.21 2.21 0 0 1-3.771 1.563");
}

</style>
