<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vevqiccwx"/><circle class="djz_49bvg"/><path class="ym7lgnghh"/><circle class="lmdll8c9g"/><path class="a8dx9gb-b"/><path class="r85xpma7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parking-sensor" /></template>
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

.r85xpma7b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.75 10.67a2.75 2.75 0 0 1 0 3.16m2.46-4.88a5.75 5.75 0 0 1 0 6.6");
}

.vevqiccwx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5V14q0-1.25 1.16-1.71l.18-.08q1.16-.46 1.77-1.55l1.03-1.82q.61-1.09 1.86-1.09h3q1.25 0 1.91 1.06l1.18 1.88q.66 1.06.66 2.31v2.5q0 1.25-1.25 1.25H4q-1.25 0-1.25-1.25m3-3.75h8.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ym7lgnghh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 19h.01");
}

</style>
