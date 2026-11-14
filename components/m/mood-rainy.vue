<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0zrccw2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mood-rainy" /></template>
<style>
.n0zrccw2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 14.5A3 3 0 0 1 5.5 9A4 4 0 0 1 12 4.5a4 4 0 0 1 7 3.25a3.5 3.5 0 0 1-1.5 6.75Zm1.5 2.75l-1 3.5m5-3.5l-1 3.5m5-3.5l-1 3.5");
}

</style>
