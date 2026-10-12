<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="dd_6j-l0z"/><path class="k_l4bzb_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rage" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.dd_6j-l0z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11h.01M15 11h.01");
}

.k_l4bzb_s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 7.75l3 1.25m6.5-1.25l-3 1.25m-5 8c1.9-1.6 4.6-1.6 6.5 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
