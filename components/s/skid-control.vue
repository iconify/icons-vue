<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkfl13i2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skid-control" /></template>
<style>
.nkfl13i2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 11.75v-1q0-1.25 1.23-1.47l.29-.06Q6.5 9 6.92 7.82l.66-1.89Q8 4.75 9.25 4.75h5.5q1.25 0 1.67 1.18l.66 1.89q.42 1.18 1.65 1.4l.29.06q1.23.22 1.23 1.47v1Q20.25 13 19 13H5q-1.25 0-1.25-1.25m3-2.75h10.5M8.5 15.25q-2.4 1.5 0 3c2.4 1.5 1.6 2 0 3m7-6q-2.4 1.5 0 3c2.4 1.5 1.6 2 0 3");
}

</style>
