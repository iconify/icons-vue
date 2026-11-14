<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f5zp0_zek"/><path class="x216ecbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treasury-covenant" /></template>
<style>
.f5zp0_zek {
  d: path("M5.5 2.5h11a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2a2 2 0 0 1 2-2m0 4v15h7.3m3.7-9.3V6.5m-8 4h5m-5 3.5h4.6m3.65 1h2.5A1.75 1.75 0 0 1 21 16.75v2.5A1.75 1.75 0 0 1 19.25 21h-2.5A1.75 1.75 0 0 1 15 19.25v-2.5A1.75 1.75 0 0 1 16.75 15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x216ecbyc {
  d: path("m16.5 18l1 1l2-2");
}

</style>
