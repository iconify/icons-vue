<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="lmycebkwb"/><path class="jc2pfdhnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:star-cluster" /></template>
<style>
.jc2pfdhnu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 5h.01M5.5 19h.01m5.99 1.5h.01");
}

.lmycebkwb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3q.84 6.16 7 7q-6.16.84-7 7q-.84-6.16-7-7q6.16-.84 7-7m7.5 10.25q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
