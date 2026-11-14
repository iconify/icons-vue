<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zv28i2bwu"/><path class="pea9wo41v"/><path class="u7lqpgbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:moat-drawbridge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pea9wo41v {
  d: path("M9 18v-5a3 3 0 0 1 6 0v5");
}

.u7lqpgbag {
  d: path("M9.772 18h4.456a1.5 1.5 0 0 1 1.221.628l.801 1.122a1.107 1.107 0 0 1-.901 1.75H8.651a1.107 1.107 0 0 1-.901-1.75l.801-1.122A1.5 1.5 0 0 1 9.772 18");
}

.zv28i2bwu {
  d: path("M4.5 18V2.5h3V5h3V2.5h3V5h3V2.5h3V18Z");
}

</style>
