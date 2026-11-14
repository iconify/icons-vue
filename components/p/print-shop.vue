<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cjtc7rbeo"/><path class="a2b2djbad"/><path class="hbjhqfbly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:print-shop" /></template>
<style>
.a2b2djbad {
  d: path("M5.25 10.25V21.5h13.5V10.25");
}

.cjtc7rbeo {
  d: path("m3 8l1.5-5h15L21 8a2.25 2.25 0 0 1-4.5 0A2.25 2.25 0 0 1 12 8a2.25 2.25 0 0 1-4.5 0A2.25 2.25 0 0 1 3 8");
}

.hbjhqfbly {
  d: path("M9.75 15.25h4.5A1.75 1.75 0 0 1 16 17a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 17a1.75 1.75 0 0 1 1.75-1.75m.25 0V13h4v2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
