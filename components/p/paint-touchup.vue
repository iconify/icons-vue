<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gmwd9dm9d"/><path class="n1m5xy8cg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paint-touchup" /></template>
<style>
.gmwd9dm9d {
  d: path("M18.364 4.636za1.25 1.25 0 0 1 0 1.768l-3.889 3.889a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768l3.889-3.889a1.25 1.25 0 0 1 1.768 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n1m5xy8cg {
  d: path("M12.707 10.293za2.5 2.5 0 0 1 0 3.535l-1.061 1.061a2.5 2.5 0 0 1-3.535 0a2.5 2.5 0 0 1 0-3.535l1.061-1.061a2.5 2.5 0 0 1 3.535 0M5.5 16.75l1.5 2a1.75 1.75 0 1 1-3 0Z");
}

</style>
