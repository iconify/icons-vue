<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m2myy79hx"/><path class="i2e6f4bsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mounted-police" /></template>
<style>
.i2e6f4bsy {
  d: path("m12 11.5l1 2.5h2.5l-2 1.75l.75 2.5l-2.25-1.5l-2.25 1.5l.75-2.5l-2-1.75H11Z");
}

.m2myy79hx {
  d: path("M3 21.5V12a9 9 0 0 1 18 0v9.5h-3.5V12a5.5 5.5 0 0 0-11 0v9.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
