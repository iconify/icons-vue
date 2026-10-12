<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="wqsfz2b7g"/><path class="wfdnybbtq"/><path class="qgmflbbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sick" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qgmflbbmk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 13.25l-3.75-2m13.25 2l3.75-2m-13.25 1.5h9.5v2A2.75 2.75 0 0 1 14 17.5h-4a2.75 2.75 0 0 1-2.75-2.75Zm2 2.5h5.5");
}

.wfdnybbtq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10h.01M15 10h.01");
}

.wqsfz2b7g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7.75c.75-.25 1.75-.5 2.5-.25m6.5.25c-.75-.25-1.75-.5-2.5-.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
