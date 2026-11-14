<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv9-x2bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spring-thaw" /></template>
<style>
.pv9-x2bjw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14C4 8.5 6.5 6 9 6s5 2.5 6.5 8m-13 0h19m-2.25-8.5c-1 1.5-1.75 2.75-1.75 4a1.75 1.75 0 0 0 3.5 0c0-1.25-.75-2.5-1.75-4M6 17.5q2-1.5 4 0t4 0");
}

</style>
