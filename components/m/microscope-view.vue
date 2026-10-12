<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="m2ggz0bnx"/><path class="coib7i0yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:microscope-view" /></template>
<style>
.coib7i0yr {
  d: path("M9.25 13.25v1m2.5-6h1.5a6 6 0 0 1 3.5 10.9v2.1m-12 0h14.5m-13.5-4h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2ggz0bnx {
  width: 5px;
  height: 10.5px;
  x: 6.75px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
