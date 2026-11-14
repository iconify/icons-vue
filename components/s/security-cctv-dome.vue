<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qr-s5mbxn"/><path class="v_s9v1w5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-cctv-dome" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qr-s5mbxn {
  d: path("M2.5 4h19m-14 0v3h9V4M5 7h14c0 6.5-3 11-7 11S5 13.5 5 7");
}

.v_s9v1w5p {
  d: path("M10 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
