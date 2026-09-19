<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x6sqm2dhy"/><path class="b2b_1nv5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:truthin" /></template>
<style>
.b2b_1nv5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.067 38.088l4.237 3.662V5.5h-13.52v5.35h-9.848V5.5H5.792l-.096 22.399C5.696 38.008 13.89 42.5 24 42.5c5.654 0 10.71-1.405 14.067-4.412");
}

.x6sqm2dhy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.84 29.646c0 2.778 2.253 4.013 5.031 4.013s5.03-1.235 5.03-4.013V18.648l-10.06-.01z");
}

</style>
