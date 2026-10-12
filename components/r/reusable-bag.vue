<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ws155eqfr"/><path class="jg2okv2kv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reusable-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg2okv2kv {
  d: path("M8.5 8.25V6.5a3.5 3.5 0 0 1 7 0v1.75m-.69 5.13a3.25 3.25 0 0 0-5.62 0m5.62 0v-2.13m0 2.13h-2.1m-3.52 3.24a3.25 3.25 0 0 0 5.62 0m-5.62 0v2.13m0-2.13h2.1");
}

.ws155eqfr {
  d: path("M5.75 8.25h12.5q2 0 1.85 1.99l-.7 9.02q-.15 1.99-2.15 1.99H6.75q-2 0-2.15-1.99l-.7-9.02q-.15-1.99 1.85-1.99");
}

</style>
