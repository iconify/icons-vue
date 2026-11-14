<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp4ff4b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tandem-skydive" /></template>
<style>
.zp4ff4b-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5c2-6.5 17-6.5 19 0q-9.5-3-19 0m3 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-9.75 7.5a2.75 2.75 0 0 1 5.5 0m3.5 0a2.75 2.75 0 0 1 5.5 0M6 12.5l-3.5-3m15.5 3l3.5-3");
}

</style>
