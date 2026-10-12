<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3l15eblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snow-sharp" /></template>
<style>
.z3l15eblu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.51 13.89a3.52 3.52 0 0 1-.49-7.01a5.06 5.06 0 0 1 9.38-1.22a3.96 3.96 0 0 1-.53 8.23Zm.74 2.86v4.5m1.95-3.37l-3.9 2.25m3.9 0l-3.9-2.25m9.45-1.13v4.5m1.95-3.37l-3.9 2.25m3.9 0l-3.9-2.25");
}

</style>
