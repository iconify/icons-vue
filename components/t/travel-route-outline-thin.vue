<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5r_prbgx"/><path class="ai0e6e9tr"/><path class="e7hm_lx5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-route-outline-thin" /></template>
<style>
.ai0e6e9tr {
  d: path("M16 19a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.e7hm_lx5y {
  d: path("M5 9v4h7v6h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5r_prbgx {
  d: path("M2 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
