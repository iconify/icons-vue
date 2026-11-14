<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsjujnbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-rate-tracker" /></template>
<style>
.hsjujnbfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.5q3.75-3.75 7.5 0t7.5 0c1.5-1.5 3-2 4-1.75M8 13l8-10M6.75 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.5 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
