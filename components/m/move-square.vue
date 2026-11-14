<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_b_ucoxv"/><path class="wmg019bqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:move-square" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_b_ucoxv {
  d: path("M9.625 3.5h4.75A6.125 6.125 0 0 1 20.5 9.625v4.75a6.125 6.125 0 0 1-6.125 6.125h-4.75A6.125 6.125 0 0 1 3.5 14.375v-4.75A6.125 6.125 0 0 1 9.625 3.5M12 6.5v11M6.5 12h11");
}

.wmg019bqa {
  d: path("M10.25 8.25L12 6.5l1.75 1.75m-3.5 7.5L12 17.5l1.75-1.75m-5.5-5.5L6.5 12l1.75 1.75m7.5-3.5L17.5 12l-1.75 1.75");
}

</style>
