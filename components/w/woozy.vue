<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="ig4m7c3qv"/><path class="d0cx5wqfm"/><path class="j28whacrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:woozy" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.d0cx5wqfm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 10.5h.01");
}

.ig4m7c3qv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9.25c.75.6 2 .6 2.75 0");
}

.j28whacrc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14 7.5l2.5.5m-8.25 8.75c.75 0 1.25-1.25 2-1.25s1 .9 1.75.9s1.25-1.15 2-1.15s1.25.6 1.75 1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
