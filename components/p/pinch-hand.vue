<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr9emgbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pinch-hand" /></template>
<style>
.xr9emgbie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.25h10.75q1.25 0 1.25 1.25t-1.25 1.25h-5q-.75 0-.75.75v3.25q0 .75.71.52l5.1-1.64q1.19-.38 1.19.87t-1.15 1.74l-5.16 2.21q-.69.3-.69 1.05v.38Q10.5 19 9 19H5.5Q3 19 3 16.5V8.75q0-2.5 2.5-2.5m14.25 2.5h1.5m-1.5 2.5h1.5");
}

</style>
