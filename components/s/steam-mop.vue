<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtka8bevf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:steam-mop" /></template>
<style>
.gtka8bevf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 17.5h9.5A1.75 1.75 0 0 1 19 19.25A1.75 1.75 0 0 1 17.25 21h-9.5A1.75 1.75 0 0 1 6 19.25a1.75 1.75 0 0 1 1.75-1.75m3.25 0l6.5-15m-12 12c-1-1.5 1-3.5 0-5.5m3 5.5c-1-1.5 1-3.5 0-5.5");
}

</style>
