<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk9_p2aug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smoke-detector" /></template>
<style>
.yk9_p2aug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3.75h13.5a1.5 1.5 0 0 1 1.5 1.5v.5a6 6 0 0 1-6 6h-4.5a6 6 0 0 1-6-6v-.5a1.5 1.5 0 0 1 1.5-1.5M9 8h6m-8.25 7.5c1.75 1.25 3.5-1.25 5.25 0s3.5 1.25 5.25 0m-10.5 4c1.75 1.25 3.5-1.25 5.25 0s3.5 1.25 5.25 0");
}

</style>
