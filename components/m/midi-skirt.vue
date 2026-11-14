<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il4xswb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:midi-skirt" /></template>
<style>
.il4xswb_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5h6A1.5 1.5 0 0 1 16.5 4A1.5 1.5 0 0 1 15 5.5H9A1.5 1.5 0 0 1 7.5 4A1.5 1.5 0 0 1 9 2.5m-.5 3l-4 10q7.5 1.5 15 0l-4-10m-6 10.75v5.25m5-5.25v5.25");
}

</style>
