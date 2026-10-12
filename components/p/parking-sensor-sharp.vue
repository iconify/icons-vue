<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="poe8olbng"/><circle class="djz_49bvg"/><path class="ym7lgnghh"/><circle class="lmdll8c9g"/><path class="a8dx9gb-b"/><path class="wejxwlayn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parking-sensor-sharp" /></template>
<style>
.a8dx9gb-b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 19h.01");
}

.djz_49bvg {
  cx: 6px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmdll8c9g {
  cx: 13px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.poe8olbng {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5v-2.75l1.16-.46l.18-.08l1.16-.46l.61-1.09l1.03-1.82l.61-1.09H13l.66 1.06l1.18 1.88l.66 1.06v5H2.75zm3-3.75h8.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wejxwlayn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.75 10.67l1.109 1.58l-1.109 1.58m2.46-4.88a5.75 5.75 0 0 1 0 6.6");
}

.ym7lgnghh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 19h.01");
}

</style>
