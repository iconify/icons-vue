<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-6dabo1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snow-rain-mix" /></template>
<style>
.t-6dabo1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.51 13.89a3.52 3.52 0 0 1-.49-7.01a5.06 5.06 0 0 1 9.38-1.22a3.96 3.96 0 0 1-.53 8.23Zm1.24 2.86l-1.5 4.5m8.5-4.5v4.5m1.95-3.37l-3.9 2.25m3.9 0l-3.9-2.25");
}

</style>
