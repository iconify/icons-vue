<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko3x0t8ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:satellite-sos" /></template>
<style>
.ko3x0t8ej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 3h1.5a1.75 1.75 0 0 1 1.75 1.75v3.5A1.75 1.75 0 0 1 11.75 10h-1.5A1.75 1.75 0 0 1 8.5 8.25v-3.5A1.75 1.75 0 0 1 10.25 3m-7.75.5h4v6h-4Zm13 0h4v6h-4Zm-9 3h2m5 0h2m-6.75 7.25a3 3 0 0 0 4.5 0m-6.5 2a6 6 0 0 0 8.5 0M18 14.5V18m0 3h.01");
}

</style>
