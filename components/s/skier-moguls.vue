<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqd_nvb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skier-moguls" /></template>
<style>
.aqd_nvb2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5a3.25 3.25 0 0 1 6.25 0a3.25 3.25 0 0 1 6.25 0a3.25 3.25 0 0 1 6.25 0M3.5 10l12-4.25q2-.75 2.25-2.25M4.5 13l13-4.5q2-.75 2.5-2.25");
}

</style>
