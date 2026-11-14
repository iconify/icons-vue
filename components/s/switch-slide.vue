<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zu737mbca"/><path class="hotno8b2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:switch-slide" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hotno8b2i {
  d: path("M7.5 10h1a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-1a2 2 0 0 1-2-2a2 2 0 0 1 2-2");
}

.zu737mbca {
  d: path("M7.5 8h9a4 4 0 0 1 4 4a4 4 0 0 1-4 4h-9a4 4 0 0 1-4-4a4 4 0 0 1 4-4");
}

</style>
