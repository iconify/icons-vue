<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx11gaceo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:opera-house" /></template>
<style>
.qx11gaceo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5h19M3 19.5Q4.5 9 11 3.5q-.5 8.5 1 16m0 0q.5-8 5-11.5q-.25 6 .75 11.5m0 0Q18 15 21 12.5q-.25 4 .25 7");
}

</style>
