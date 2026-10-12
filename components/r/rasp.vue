<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wwui0ibtr"/><path class="etcpiyqid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rasp" /></template>
<style>
.etcpiyqid {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.22 12.78h.01m2.64-2.65h.01");
}

.wwui0ibtr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.15 16.67l1.76-1.76q1.24-1.24 2.48 0l.7.7q1.24 1.24 0 2.48l-1.76 1.76q-1.24 1.24-2.48 0l-.7-.7q-1.24-1.24 0-2.48m3.57-3.84l9.47-8.23q.75-.66 1.46.05l.7.7q.71.71.05 1.46l-8.23 9.47q-.66.75-1.37.04L7.68 14.2q-.71-.71.04-1.37");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
