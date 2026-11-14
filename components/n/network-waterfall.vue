<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aep1608qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:network-waterfall" /></template>
<style>
.aep1608qc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v19M7.75 4h4.5A1.75 1.75 0 0 1 14 5.75a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 6 5.75A1.75 1.75 0 0 1 7.75 4m4 6.25h4.5A1.75 1.75 0 0 1 18 12a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 10 12a1.75 1.75 0 0 1 1.75-1.75m3.5 6.25h4.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 19.75 20h-4.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
