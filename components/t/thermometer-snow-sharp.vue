<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jcjg7w64i"/><circle class="unvuys2lq"/><path class="fox2hyg_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thermometer-snow-sharp" /></template>
<style>
.fox2hyg_x {
  d: path("M17.75 14.25v4.5m1.95-3.37l-3.9 2.25m3.9 0l-3.9-2.25");
}

.jcjg7w64i {
  d: path("M5.5 13.55V5.5a2.5 2.5 0 0 1 5 0v8.05a4.25 4.25 0 1 1-5 0ZM8 15.5v-2.25");
}

.unvuys2lq {
  cx: 8px;
  cy: 17px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
