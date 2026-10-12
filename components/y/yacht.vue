<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tucil9dnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yacht" /></template>
<style>
.tucil9dnm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.5h16.5q1 0 .67.94l-1.09 3.12q-.33.94-1.33.94H7.25q-1 0-1.57-.82l-2.36-3.36q-.57-.82.43-.82m4 0l1.75-4h5.75l3 4Zm4.75-4V5.25M2.75 20.5q2.31-1.5 4.62 0c2.31 1.5 3.09 1 4.63 0s3.08-1 4.63 0s3.08 1 4.62 0");
}

</style>
