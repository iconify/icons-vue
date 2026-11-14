<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lnuj2qkqk"/><path class="rhi2ieb2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:presentation-line" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lnuj2qkqk {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v6.5A3.5 3.5 0 0 1 18 16H6a3.5 3.5 0 0 1-3.5-3.5V6A3.5 3.5 0 0 1 6 2.5m2 19l2-5.5m6 5.5L14 16");
}

.rhi2ieb2n {
  d: path("M6.5 12.5L10 9l3 2l4.5-5");
}

</style>
