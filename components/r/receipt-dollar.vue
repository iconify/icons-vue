<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t14_i3m5x"/><path class="aydsmo20i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:receipt-dollar" /></template>
<style>
.aydsmo20i {
  d: path("M14.25 8.75C14 8 13.2 7.5 12 7.5c-1.25 0-2.25.7-2.25 1.75c0 2.25 4.5 1.5 4.5 4c0 1.05-1 1.75-2.25 1.75s-2.1-.5-2.25-1.25m2.25-8V7.5m0 7.5v1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t14_i3m5x {
  d: path("M6.75 3h10.5A1.75 1.75 0 0 1 19 4.75v14.234A1.17 1.17 0 0 1 17.25 20l-.882-.504a1.75 1.75 0 0 0-1.736 0l-1.764 1.008a1.75 1.75 0 0 1-1.736 0l-1.764-1.008a1.75 1.75 0 0 0-1.736 0L6.75 20A1.17 1.17 0 0 1 5 18.984V4.75A1.75 1.75 0 0 1 6.75 3");
}

</style>
