<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dh-6rabem"/><path class="w8khlpb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:newsprint" /></template>
<style>
.dh-6rabem {
  d: path("M6.5 19V4.5a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2V19a2.5 2.5 0 0 1-2.5 2.5H5A2.5 2.5 0 0 1 2.5 19V9.5h4m3-3h9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8khlpb6y {
  d: path("M11 10h1a1.5 1.5 0 0 1 1.5 1.5V13a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 9.5 13v-1.5A1.5 1.5 0 0 1 11 10m5.25 2.25h2.25M9.5 18h9");
}

</style>
