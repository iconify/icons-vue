<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4s9uyzab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trash-bin-kitchen" /></template>
<style>
.n4s9uyzab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 6.5a6.75 3.75 0 0 1 13.5 0ZM6.5 9h11q1.5 0 1.35 1.49l-.95 9.27q-.15 1.49-1.65 1.49h-8.5q-1.5 0-1.65-1.49l-.95-9.27Q5 9 6.5 9m3.5 3.25v5.5m4-5.5v5.5m4.4 1.5h2.85");
}

</style>
