<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pcqc5v7hp"/><path class="l37r4-8ho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:restaurants-nearby" /></template>
<style>
.l37r4-8ho {
  d: path("M10 9.75V8.5a2 2 0 0 1 4 0v1.25M2.5 16.5h19M5 16.5l2 3h10l2-3M7 14a5.5 5.5 0 0 1 2.25-2.5");
}

.pcqc5v7hp {
  d: path("M3.5 16.5c0-9 17-9 17 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
