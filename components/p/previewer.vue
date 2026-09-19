<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="xnqsqjfan"/><circle class="ryoukldos"/><circle class="hwjh1e4pw"/><circle class="a7o870w6a"/><circle class="m_ff33-8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:previewer" /></template>
<style>
.a7o870w6a {
  cx: 29.907px;
  cy: 13.165px;
  r: 2.978px;
}

.hwjh1e4pw {
  cx: 17.996px;
  cy: 13.165px;
  r: 2.978px;
}

.m_ff33-8q {
  cx: 37.241px;
  cy: 22.705px;
  r: 2.978px;
}

.ryoukldos {
  cx: 10.607px;
  cy: 22.705px;
  r: 2.978px;
}

.xnqsqjfan {
  d: path("M24.449 2.52c-12.123 0-21.95 9.63-21.949 21.508c0 10.748 8.097 19.846 18.963 21.307c6.132 1.012 7.495-3.555 5.625-5.632c-1.974-2.193-.934-6.318 3.742-5.965c4.181.316 9.846.49 13.452-6.551c3.044-5.944-.53-13.402-.91-14.052C39.43 6.56 32.23 2.521 24.448 2.521Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
