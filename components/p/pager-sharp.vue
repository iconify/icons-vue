<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="q1oy59b8h"/><path class="fjgjo__bn"/><path class="qy1h400-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pager-sharp" /></template>
<style>
.fjgjo__bn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 8.75h12.5V12H5.75z");
}

.q1oy59b8h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h18.5v12.5H2.75z");
}

.qy1h400-r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16h.01M12 16h.01M16 16h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
