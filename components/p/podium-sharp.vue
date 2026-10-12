<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dhalwcbhj"/><path class="sn2fxebfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:podium-sharp" /></template>
<style>
.dhalwcbhj {
  d: path("M2.75 21.25V11.5h6V4.75h6.5v9H21v7.5Z");
}

.sn2fxebfr {
  d: path("m11 9l1.25-1v5.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
