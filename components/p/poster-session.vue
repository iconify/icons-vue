<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5vn_ub1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:poster-session" /></template>
<style>
.j5vn_ub1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.5H21.5v12H10.75Zm5.25 12v7M13.5 6.25h5.25m-5.25 4h3M3 12.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-.5 9c0-2.5 1.25-3.75 3-3.75s3 1.25 3 3.75");
}

</style>
