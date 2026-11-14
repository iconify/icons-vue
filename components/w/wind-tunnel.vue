<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7k21fbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wind-tunnel" /></template>
<style>
.e7k21fbhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5c4.5 0 5.5 3 9.5 3h9.5m-19 14c4.5 0 5.5-3 9.5-3h9.5M4.5 12H19m-2.25-2.25L19 12l-2.25 2.25");
}

</style>
