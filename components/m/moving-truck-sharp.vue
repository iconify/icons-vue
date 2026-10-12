<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ahdns6l3u"/><circle class="pk183qw0r"/><path class="ip1jjbrmk"/><circle class="xw30-oz_l"/><path class="pr2iyxt7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moving-truck-sharp" /></template>
<style>
.ahdns6l3u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5V3.75h18.5V8H16.5v3h2.9l.45.6L21 13.15l.25.377V17H2.75v-1Zm13.75 6v6M6 6.75v7");
}

.ip1jjbrmk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 19h.01");
}

.pk183qw0r {
  cx: 6.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pr2iyxt7r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 19h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xw30-oz_l {
  cx: 18px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
