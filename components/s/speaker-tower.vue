<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x8ry6ibly"/><circle class="p98yu_b-b"/><circle class="nxcjk5gco"/><path class="nbwtimgyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speaker-tower" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbwtimgyq {
  d: path("M8.75 19.25v2m6.5-2v2");
}

.nxcjk5gco {
  cx: 12px;
  cy: 14px;
  r: 1.75px;
}

.p98yu_b-b {
  cx: 12px;
  cy: 7.75px;
  r: 1.75px;
}

.x8ry6ibly {
  width: 10px;
  height: 16.5px;
  x: 7px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
