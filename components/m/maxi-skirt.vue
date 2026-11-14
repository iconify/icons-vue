<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koyzwnbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:maxi-skirt" /></template>
<style>
.koyzwnbuk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h5A1.5 1.5 0 0 1 16 4a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 8 4a1.5 1.5 0 0 1 1.5-1.5m-.5 3l-4.5 15q7.5 1.5 15 0L15 5.5m-4.75 5L9.5 18m4.25-7.5l.75 7.5");
}

</style>
