<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycgdmsbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medicine-x" /></template>
<style>
.ycgdmsbrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.636 12.414l7.778-7.778a3.5 3.5 0 0 1 4.95 0a3.5 3.5 0 0 1 0 4.95l-7.778 7.778a3.5 3.5 0 0 1-4.95 0a3.5 3.5 0 0 1 0-4.95m3.889-3.889l4.95 4.95M15.5 15.5l5 5m0-5l-5 5");
}

</style>
