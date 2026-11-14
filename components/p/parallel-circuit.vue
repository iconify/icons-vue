<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_yd_zbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parallel-circuit" /></template>
<style>
.i_yd_zbom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 6.5H5v11h4.25m5.5-11H19v11h-4.25M2.5 12H5m14 0h2.5M9.25 6.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm0 11a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm.75-13l4 4m0-4l-4 4m0 7l4 4m0-4l-4 4");
}

</style>
