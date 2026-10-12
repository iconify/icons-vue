<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="tgj7e0bzn"/><path class="zr1lbob2b"/><path class="me5kafbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tag-person" /></template>
<style>
.me5kafbop {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 11.75h.01");
}

.tgj7e0bzn {
  cx: 8.5px;
  cy: 7.75px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zr1lbob2b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.25h10a.75.75 0 0 0 .75-.75c0-3-2.6-5.25-5.75-5.25S2.75 16.5 2.75 19.5a.75.75 0 0 0 .75.75m14-12h2.75a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H17.5l-2.5-3.5Z");
}

</style>
