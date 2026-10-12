<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nl8hhdbnn"/><path class="kprwtsbgu"/><circle class="uvig46c8n"/><path class="kny_pabcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safe-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kny_pabcv {
  d: path("M13 11.25V9");
}

.kprwtsbgu {
  d: path("M6.5 18.5v2m11-2v2M5.5 7v1.75m0 4.75v1.75");
}

.nl8hhdbnn {
  width: 18.5px;
  height: 14.75px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

.uvig46c8n {
  cx: 13px;
  cy: 11.25px;
  r: 3.5px;
}

</style>
