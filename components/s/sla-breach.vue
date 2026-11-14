<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvlf9xbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sla-breach" /></template>
<style>
.zvlf9xbox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h11M4 21h11M5.5 3v2.5q0 3.5 4 6.5t4 6.5V21m0-18v2.5q0 3.5-4 6.5t-4 6.5V21M18 14.75v3.5M18 21h.01");
}

</style>
