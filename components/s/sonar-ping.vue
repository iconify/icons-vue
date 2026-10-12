<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="svuooibzi"/><path class="siwf3tbbo"/><circle class="taq4_hb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sonar-ping" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.siwf3tbbo {
  d: path("M8.5 8.25a5.25 5.25 0 0 1 0 7.5m3-10.5a9.5 9.5 0 0 1 0 13.5");
}

.svuooibzi {
  cx: 4.75px;
  cy: 12px;
  r: 2px;
}

.taq4_hb2a {
  cx: 18.75px;
  cy: 12px;
  r: 2px;
}

</style>
