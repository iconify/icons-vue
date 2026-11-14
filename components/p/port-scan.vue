<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyx1oml6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:port-scan" /></template>
<style>
.oyx1oml6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3.5h13A1.5 1.5 0 0 1 20 5v5.5a1.5 1.5 0 0 1-1.5 1.5H16v2.5H8V12H5.5A1.5 1.5 0 0 1 4 10.5V5a1.5 1.5 0 0 1 1.5-1.5Zm2.5 2V8m3-2.5V8m3-2.5V8m1.25 9.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

</style>
