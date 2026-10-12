<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="i_1r5-b4t"/><path class="vk6l63buw"/><circle class="zofk-exqs"/><circle class="jz58izt2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ride-share" /></template>
<style>
.i_1r5-b4t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.24 13.35l1.27-2.95Q5 9.25 6.25 9.25h11.5q1.25 0 1.74 1.15l1.27 2.95q.49 1.15.49 2.4v2Q21.25 19 20 19H4q-1.25 0-1.25-1.25v-2q0-1.25.49-2.4M5.5 19v2.25m13-2.25v2.25");
}

.jz58izt2b {
  cx: 15px;
  cy: 4.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vk6l63buw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 15h.01m11.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zofk-exqs {
  cx: 9px;
  cy: 4.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
