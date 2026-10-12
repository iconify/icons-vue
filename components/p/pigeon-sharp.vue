<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dleaimyvx"/><path class="sgisc_q5o"/><path class="xzw-2u4_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pigeon-sharp" /></template>
<style>
.dleaimyvx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7V4.5H10v3.36l-.4.64c3.65.75 7.15 2.75 9.15 4.5L21 14.25l1.313.75H18c-1.25 2-3.5 3.25-6 3.25c-4 0-7.75-2-7.75-5.5V10.6L6.5 9.25l-1-.917z");
}

.sgisc_q5o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.75 10.25l2.837 1.621l2.663-1.521m.25 2.15l2.625 1.875l3.375.375M5.6 6.9l-1.85.7m6.75 10.55L9 20.75m4.5-2.65l.5 2.65");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xzw-2u4_v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.6 6.6h.01");
}

</style>
