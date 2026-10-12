<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mgabo7jze"/><path class="nfvs04hze"/><rect class="g-s2as_qt"/><path class="ym2krgbbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tablet-and-phone" /></template>
<style>
.g-s2as_qt {
  width: 6px;
  height: 12px;
  x: 15.25px;
  y: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.mgabo7jze {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75h10q2 0 2 1.75t-2 1.75h-1.5q-2 0-2 2v11q0 2-2 2h-4.5q-2 0-2-2V4.75q0-2 2-2");
}

.nfvs04hze {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 18h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ym2krgbbp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 18.5H19");
}

</style>
