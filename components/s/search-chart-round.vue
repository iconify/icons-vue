<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy_dmrbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:search-chart-round" /></template>
<style>
.iy_dmrbmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10a7 7 0 1 0 14 0a7 7 0 0 0-14 0m12 5l6 6M7 12l1-1a1.414 1.414 0 0 1 2 0l1 1l2-4");
}

</style>
