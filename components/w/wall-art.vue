<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b643rsxuq"/><path class="m-uiwcbld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wall-art" /></template>
<style>
.b643rsxuq {
  d: path("M2.5 6h19v14h-19ZM7 6l5-3.5L17 6");
}

.m-uiwcbld {
  d: path("m5.5 17l4-5l3.25 3.5L15 13l3.5 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
