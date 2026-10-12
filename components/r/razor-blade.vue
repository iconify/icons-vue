<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="dkkiqwb0f"/><path class="cmo1wrcay"/><path class="on78oebbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:razor-blade" /></template>
<style>
.cmo1wrcay {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 12h8");
}

.dkkiqwb0f {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.on78oebbl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 12h.01M19 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
