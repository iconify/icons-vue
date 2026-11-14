<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coog30akl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:org-chart-horizontal" /></template>
<style>
.coog30akl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m13-6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m0 13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M8 12h4m4-6.5h-2.5A1.5 1.5 0 0 0 12 7v10a1.5 1.5 0 0 0 1.5 1.5H16");
}

</style>
