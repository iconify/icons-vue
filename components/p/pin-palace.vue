<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l2be6xbox"/><path class="nbip-qb9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-palace" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l2be6xbox {
  d: path("M3.5 21V3.5H7v3h3.25v-3h3.5v3H17v-3h3.5V21Z");
}

.nbip-qb9h {
  d: path("M9.5 21v-5.5a2.5 2.5 0 0 1 5 0V21m-8-11v3.5m11-3.5v3.5");
}

</style>
