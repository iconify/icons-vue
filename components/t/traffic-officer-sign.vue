<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-_t04mdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traffic-officer-sign" /></template>
<style>
.w-_t04mdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.25H12m-6.75 0v-2.5q2.5-2 5 0v2.5m-5 0V9a2.5 2.5 0 0 0 5 0V7.25M2.5 21.5V18A3.5 3.5 0 0 1 6 14.5h3.5A3.5 3.5 0 0 1 13 18v3.5m-1.75-6.75l5.75-4m0-6.5h2.5l2 2v2.5l-2 2H17l-2-2v-2.5Z");
}

</style>
