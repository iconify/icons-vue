<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l73pdpbsu"/><path class="deyovgb-o"/><path class="hxrso3blh"/><path class="sqcm0db3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:milestone-chart" /></template>
<style>
.deyovgb-o {
  d: path("M5.5 18c4.5-.5 9-5.5 14.5-13.5");
}

.hxrso3blh {
  fill: currentColor;
  d: path("M7.25 17a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm5-4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm4.25-5A1.25 1.25 0 1 0 19 8a1.25 1.25 0 1 0-2.5 0Z");
}

.l73pdpbsu {
  d: path("M3.5 2.5v18h18");
}

.sqcm0db3y {
  d: path("M7 7h2.5M7 11h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
