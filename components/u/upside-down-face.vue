<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="o0rhzo4yy"/><path class="af85zkb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:upside-down-face" /></template>
<style>
.af85zkb7t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 14h.01M15 14h.01");
}

.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o0rhzo4yy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9.75c.9-1.3 2.1-2 3.5-2s2.6.7 3.5 2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
