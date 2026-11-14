<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv7ibglfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:takt-time" /></template>
<style>
.bv7ibglfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.086 20.5h5.828a1.75 1.75 0 0 0 1.724-2.054l-2.383-13.5A1.75 1.75 0 0 0 12.532 3.5h-1.064a1.75 1.75 0 0 0-1.723 1.446l-2.383 13.5A1.75 1.75 0 0 0 9.086 20.5m2.914-4L15.5 7M9 16.5h6");
}

</style>
