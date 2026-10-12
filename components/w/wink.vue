<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="m1nbwhb7d"/><path class="o6r90jb_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wink" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1nbwhb7d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10h.01");
}

.o6r90jb_v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 10.25c.7-.6 1.8-.6 2.5 0m-7.75 4c.9 1.3 2.1 2 3.5 2s2.6-.7 3.5-2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
