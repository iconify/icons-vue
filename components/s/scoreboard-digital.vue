<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ebf-dbb8f"/><path class="kz767xb1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scoreboard-digital" /></template>
<style>
.ebf-dbb8f {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5V13a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13V6.5A3.5 3.5 0 0 1 6 3m1 13.5v5m10-5v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kz767xb1t {
  d: path("M7.5 6.5h1A1.5 1.5 0 0 1 10 8v3.5A1.5 1.5 0 0 1 8.5 13h-1A1.5 1.5 0 0 1 6 11.5V8a1.5 1.5 0 0 1 1.5-1.5m8.5 0V13m-1.5-5L16 6.5");
}

</style>
