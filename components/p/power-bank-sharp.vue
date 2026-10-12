<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gwly89btw"/><path class="fp8m5kchp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:power-bank-sharp" /></template>
<style>
.fp8m5kchp {
  d: path("M10.5 8.75L8.25 12h3.5L9.5 15.25");
}

.gwly89btw {
  d: path("M2.75 5.75h14v12.5h-14zm14 6.25h4v9.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
