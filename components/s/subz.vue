<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wxbme9kle"/><path class="sjxn19_9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:subz" /></template>
<style>
.sjxn19_9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 37.5v-21a2 2 0 0 0-2-2h-35a2 2 0 0 0-2 2v21a2 2 0 0 0 2 2h35a2 2 0 0 0 2-2m-6.61-26.13V9.62a1.12 1.12 0 0 0-1.12-1.12H12.23a1.12 1.12 0 0 0-1.12 1.12v1.75m28.78 3.13v-2a1.12 1.12 0 0 0-1.12-1.12H9.23a1.12 1.12 0 0 0-1.12 1.12v2");
}

.wxbme9kle {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.51 19.5l13 7.5l-13 7.5z");
}

</style>
