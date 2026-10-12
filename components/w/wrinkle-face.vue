<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="rio_yrb4k"/><path class="ci8tqvbtg"/><path class="oeh1t_get"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wrinkle-face" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ci8tqvbtg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11.75h.01m5.99 0h.01");
}

.oeh1t_get {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 11.25l-1 .5M6 13l-1-.25m13-1.5l1 .5M18 13l1-.25M9.5 16.5c1.6 1 3.4 1 5 0");
}

.rio_yrb4k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.25c2.6-.8 5.4-.8 8 0M9 8.5q3-.9 6 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
