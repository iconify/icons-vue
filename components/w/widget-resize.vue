<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu2ev1byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:widget-resize" /></template>
<style>
.yu2ev1byk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 2.5h6.75A4.375 4.375 0 0 1 18 6.875v6.75A4.375 4.375 0 0 1 13.625 18h-6.75A4.375 4.375 0 0 1 2.5 13.625v-6.75A4.375 4.375 0 0 1 6.875 2.5M2.5 8.5H18M7.5 4.25h.01m2.74 0h.01m2.74 0h.01M7.5 6.75h.01m2.74 0h.01m2.74 0h.01m.49 6.75l8 8m-4.75 0h4.75v-4.75");
}

</style>
