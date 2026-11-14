<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v0h5ag0hv"/><path class="l4zt5ydsj"/><path class="qv8s9kl7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meter-bar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4zt5ydsj {
  fill: currentColor;
  d: path("M5.75 8.5h8A1.25 1.25 0 0 1 15 9.75A1.25 1.25 0 0 1 13.75 11h-8A1.25 1.25 0 0 1 4.5 9.75A1.25 1.25 0 0 1 5.75 8.5");
}

.qv8s9kl7k {
  d: path("M3.5 16.5v3m4.5-3v2m4-2v3m4-3v2m4.5-2v3");
}

.v0h5ag0hv {
  d: path("M5.75 6h12.5A3.75 3.75 0 0 1 22 9.75a3.75 3.75 0 0 1-3.75 3.75H5.75A3.75 3.75 0 0 1 2 9.75A3.75 3.75 0 0 1 5.75 6");
}

</style>
