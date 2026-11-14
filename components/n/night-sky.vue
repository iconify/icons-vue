<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_lvzqq5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:night-sky" /></template>
<style>
.r_lvzqq5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 3a6.5 6.5 0 1 0 4 9a5.5 5.5 0 0 1-4-9m7.5.25Q19 5 20.75 5.5Q19 6 18.5 7.75Q18 6 16.25 5.5Q18 5 18.5 3.25m.5 11.5q.5 1.25 1.75 1.75q-1.25.5-1.75 1.75q-.5-1.25-1.75-1.75Q18.5 16 19 14.75M12.5 18q.25 1.25 1.5 1.5q-1.25.25-1.5 1.5q-.25-1.25-1.5-1.5q1.25-.25 1.5-1.5");
}

</style>
