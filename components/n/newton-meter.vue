<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d7yecue3j"/><path class="j4_d2ebhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:newton-meter" /></template>
<style>
.d7yecue3j {
  d: path("M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4_d2ebhl {
  d: path("M11.625 6h.75A2.625 2.625 0 0 1 15 8.625v5.75A2.625 2.625 0 0 1 12.375 17h-.75A2.625 2.625 0 0 1 9 14.375v-5.75A2.625 2.625 0 0 1 11.625 6M12 17v2.5a2 2 0 0 1-4 0m1-10h2.5m-2.5 4h2.5");
}

</style>
