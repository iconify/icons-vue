<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o5zub0bun"/><path class="iu76q6a5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-phone" /></template>
<style>
.iu76q6a5g {
  fill: currentColor;
  d: path("M10.25 16.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.o5zub0bun {
  d: path("M3 9V8c0-3 3.5-4.5 9-4.5S21 5 21 8v1h-4.5V7.5h-9V9Zm4 2.75h10L20.5 21h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
