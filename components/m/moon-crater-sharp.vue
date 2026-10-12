<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="m4l-9ybuj"/><circle class="cz52nob5z"/><circle class="wtqeeyb2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-crater-sharp" /></template>
<style>
.cz52nob5z {
  cx: 9px;
  cy: 9.5px;
  r: 2px;
}

.m4l-9ybuj {
  cx: 12px;
  cy: 12px;
  r: 9px;
}

.wtqeeyb2r {
  cx: 14.5px;
  cy: 15px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
