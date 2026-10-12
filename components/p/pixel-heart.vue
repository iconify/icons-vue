<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="js35libpj"/><rect class="nd9lx2exe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pixel-heart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.js35libpj {
  d: path("M6.25 4.5h4q.5 0 .5.5v1.5q0 .5.5.5h1.5q.5 0 .5-.5V5q0-.5.5-.5h4q.5 0 .5.5v1.5q0 .5.5.5h1.5q.5 0 .5.5v4q0 .5-.5.5h-1.5q-.5 0-.5.5V14q0 .5-.5.5h-1.5q-.5 0-.5.5v1.5q0 .5-.5.5h-1.5q-.5 0-.5.5V19q0 .5-.5.5h-1.5q-.5 0-.5-.5v-1.5q0-.5-.5-.5h-1.5q-.5 0-.5-.5V15q0-.5-.5-.5h-1.5q-.5 0-.5-.5v-1.5q0-.5-.5-.5h-1.5q-.5 0-.5-.5v-4q0-.5.5-.5h1.5q.5 0 .5-.5V5q0-.5.5-.5");
}

.nd9lx2exe {
  width: 1.5px;
  height: 1.5px;
  x: 6.25px;
  y: 7.5px;
  rx: 0.4px;
}

</style>
