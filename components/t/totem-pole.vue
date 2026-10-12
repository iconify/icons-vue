<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="k1byavq2v"/><path class="k_1lzbbwc"/><path class="vsw33ccsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:totem-pole" /></template>
<style>
.k_1lzbbwc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.26 5.61l-3.77-.72q-.74-.14-.5.57l1.02 3.08q.24.71.99.71h2.25Q8 9.25 8 8.5v-2q0-.75-.74-.89m9.48 0l3.77-.72q.74-.14.5.57l-1.02 3.08q-.24.71-.99.71h-2.25q-.75 0-.75-.75v-2q0-.75.74-.89M8.75 9.25h6.5m-6.5 6h6.5m-5-2.25h3.5m-3.5 6h3.5");
}

.k1byavq2v {
  width: 8px;
  height: 18.5px;
  x: 8px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.vsw33ccsk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 6h.01m2.99 0h.01m-3.01 5.25h.01m2.99 0h.01m-3.01 6h.01m2.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
