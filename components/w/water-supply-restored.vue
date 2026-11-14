<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4ewbcb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-supply-restored" /></template>
<style>
.j4ewbcb6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h6a4.5 4.5 0 0 1 4.5 4.5V12H8.5v-1.5h-6m3-4.5V3m-2 0h4m3.25 12S9 17.25 9 18.75a1.75 1.75 0 0 0 3.5 0c0-1.5-1.75-3.75-1.75-3.75m4.75 3.5l2.25 2.25L22 16.5");
}

</style>
