<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_ex8-s5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pen-holder" /></template>
<style>
.l_ex8-s5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 11.25h10q1.75 0 1.53 1.74l-.81 6.52q-.22 1.74-1.97 1.74h-7.5q-1.75 0-1.97-1.74l-.81-6.52Q5.25 11.25 7 11.25M6.75 15h10.5m-8.5-3.75l-2-8m5.25 8v-8.5m3.25 8.5l3-7");
}

</style>
