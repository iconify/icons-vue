<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp5ct3bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:turbulence" /></template>
<style>
.vp5ct3bwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5H7A3.5 3.5 0 1 0 3.5 14m18-7.5H17a3.5 3.5 0 1 0 3.5 3.5m-18-3.5q2.25-2 4.5 0t4.5 0m1 11q2.25 2 4.5 0t4.5 0");
}

</style>
