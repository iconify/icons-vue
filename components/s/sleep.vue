<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu-7asbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sleep" /></template>
<style>
.pu-7asbvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 15A8 8 0 1 1 9 4a7.25 7.25 0 0 0 9 11Zm-.5-11.25Q17.5 6 19.75 6Q17.5 6 17.5 8.25Q17.5 6 15.25 6q2.25 0 2.25-2.25Zm3 5.75q0 1.5 1.5 1.5q-1.5 0-1.5 1.5q0-1.5-1.5-1.5q1.5 0 1.5-1.5Z");
}

</style>
