<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4_-8cc6c"/><path class="qz_bnctsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:monolith" /></template>
<style>
.f4_-8cc6c {
  d: path("M6.75 6h7a1.75 1.75 0 0 1 1.75 1.75v12a1.75 1.75 0 0 1-1.75 1.75h-7A1.75 1.75 0 0 1 5 19.75v-12A1.75 1.75 0 0 1 6.75 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qz_bnctsg {
  d: path("m5 6l3.5-3.5H19V18l-3.5 3.5m0-15.5L19 2.5");
}

</style>
