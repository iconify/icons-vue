<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpce0ifjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:traffic-officer-sign" /></template>
<style>
.fpce0ifjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.25H12m-6.75 0v-2.5q2.5-2 5 0v2.5m-5 0V9a2.5 2.5 0 0 0 5 0V7.25M2.5 21.5V18A3.5 3.5 0 0 1 6 14.5h3.5A3.5 3.5 0 0 1 13 18v3.5m-1.75-6.75l5.75-4m.621-6.5h1.258a1.5 1.5 0 0 1 1.06.439l1.122 1.122a1.5 1.5 0 0 1 .439 1.06v1.258a1.5 1.5 0 0 1-.439 1.06l-1.122 1.122a1.5 1.5 0 0 1-1.06.439h-1.258a1.5 1.5 0 0 1-1.06-.439l-1.122-1.122A1.5 1.5 0 0 1 15 8.129V6.871a1.5 1.5 0 0 1 .439-1.06l1.122-1.122a1.5 1.5 0 0 1 1.06-.439");
}

</style>
