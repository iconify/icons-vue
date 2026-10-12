<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ry59zbcad"/><path class="i32saebhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-zoom-out-sharp" /></template>
<style>
.i32saebhb {
  d: path("M8 11h6m2.5 5.5L21 21");
}

.ry59zbcad {
  cx: 11px;
  cy: 11px;
  r: 7.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
