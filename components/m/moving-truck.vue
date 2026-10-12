<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jmqefchxe"/><circle class="pk183qw0r"/><path class="ip1jjbrmk"/><circle class="xw30-oz_l"/><path class="pr2iyxt7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moving-truck" /></template>
<style>
.ip1jjbrmk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 19h.01");
}

.jmqefchxe {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5A1.25 1.25 0 0 1 4 3.75h16A1.25 1.25 0 0 1 21.25 5v1.75A1.25 1.25 0 0 1 20 8h-3.5v3h2.15a1.5 1.5 0 0 1 1.2.6L21 13.15a1.5 1.5 0 0 1 .25.83V16a1 1 0 0 1-1 1H3.75a1 1 0 0 1-1-1Zm13.75 6v6M6 6.75v7");
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

.xw30-oz_l {
  cx: 18px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
