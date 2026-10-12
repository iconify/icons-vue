<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-nnonnmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-lander" /></template>
<style>
.e-nnonnmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3.5h5q1 0 1.51.86l1.98 3.28q.51.86 0 1.72l-1.98 3.28q-.51.86-1.51.86h-5q-1 0-1.51-.86L6.01 9.36q-.51-.86 0-1.72l1.98-3.28Q8.5 3.5 9.5 3.5m-1 10L5 20.75m7-7.25v7.25m3.5-7.25l3.5 7.25");
}

</style>
