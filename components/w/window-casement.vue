<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4uk_mbos"/><path class="co47a86tr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:window-casement" /></template>
<style>
.co47a86tr {
  d: path("m16.005 3.716l4 1.428A1.5 1.5 0 0 1 21 6.557v10.886a1.5 1.5 0 0 1-.995 1.413l-4 1.428A1.5 1.5 0 0 1 14 18.871V5.129a1.5 1.5 0 0 1 2.005-1.413M3 12h18");
}

.f4uk_mbos {
  d: path("M5.625 3h5.75A2.625 2.625 0 0 1 14 5.625v12.75A2.625 2.625 0 0 1 11.375 21h-5.75A2.625 2.625 0 0 1 3 18.375V5.625A2.625 2.625 0 0 1 5.625 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
