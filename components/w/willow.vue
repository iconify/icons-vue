<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njelx0b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:willow" /></template>
<style>
.njelx0b0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25V11m0 0L7 4.5m5 6.5l5-6.5m-10 0Q3.625 5.25 3.25 15M9.5 7.75c-1.5 1.25-2 3.75-2 9M17 4.5q3.375.75 3.75 10.5M14.5 7.75c1.5 1.25 2 3.75 2 9");
}

</style>
