<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="l4ue09bky"/><circle class="uoq8kdhhu"/><circle class="ytt_f39jy"/><circle class="y5b-5i10u"/><circle class="x1j4haclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nedir-ne-demek" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.l4ue09bky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.352 21.812v-8l5.299 8v-8m2.718 8v-8h1.8c1.9 0 3.5 1.6 3.5 3.5v1c0 1.9-1.6 3.5-3.5 3.5zm-16.037 0v-8l5.299 8v-8m7.095 13.966v6.409h3.204m-8.897-6.409h4.166l-4.166 6.409h4.166M8.58 33.466c.4.48.881.721 1.602.721h.962c.881 0 1.602-.72 1.602-1.602h0c0-.882-.72-1.603-1.602-1.603h-1.042A1.607 1.607 0 0 1 8.5 29.38h0c0-.881.721-1.602 1.602-1.602h.962c.72 0 1.201.16 1.602.72m17.782-.72v4.246c0 1.202.961 2.163 2.083 2.163s2.083-.96 2.083-2.163v-4.246m-18.266 6.41a2.07 2.07 0 0 1-2.083-2.083v-2.163c0-1.202.961-2.164 2.083-2.164h0c1.202 0 2.163.962 2.163 2.164v2.083a2.154 2.154 0 0 1-2.163 2.163m19.787-6.41v6.409m0-2.243l3.365-4.166m0 6.409l-2.564-3.204");
}

.uoq8kdhhu {
  cx: 33.649px;
  cy: 26.163px;
  r: 0.75px;
  fill: currentColor;
}

.x1j4haclz {
  cx: 15.262px;
  cy: 26.163px;
  r: 0.75px;
  fill: currentColor;
}

.y5b-5i10u {
  cx: 17.505px;
  cy: 26.163px;
  r: 0.75px;
  fill: currentColor;
}

.ytt_f39jy {
  cx: 31.405px;
  cy: 26.163px;
  r: 0.75px;
  fill: currentColor;
}

</style>
