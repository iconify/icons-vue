<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g_mggh42j"/><path class="q_bb4gb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:penalty-kick" /></template>
<style>
.g_mggh42j {
  d: path("M5 10.25a7 7 0 1 0 14 0a7 7 0 1 0-14 0M4.5 20.5h15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q_bb4gb7c {
  d: path("m12.86 8.352l.697.488a1.5 1.5 0 0 1 .55 1.742l-.248.681a1.5 1.5 0 0 1-1.41.987h-.898a1.5 1.5 0 0 1-1.41-.987l-.248-.681a1.5 1.5 0 0 1 .55-1.742l.697-.488a1.5 1.5 0 0 1 1.72 0M12 7.75v-4.5m2.5 6.25L18.75 8m-5.25 4.25L16 16m-5.5-3.75L8 16m1.5-6.5L5.25 8");
}

</style>
