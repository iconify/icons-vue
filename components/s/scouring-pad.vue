<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l9mrlibxq"/><path class="z9ia0ab0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scouring-pad" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9mrlibxq {
  d: path("M7.25 9.5h9.5a4.75 4.75 0 0 1 4.75 4.75A4.75 4.75 0 0 1 16.75 19h-9.5a4.75 4.75 0 0 1-4.75-4.75A4.75 4.75 0 0 1 7.25 9.5M8.75 6h6.5A1.75 1.75 0 0 1 17 7.75a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 7.75A1.75 1.75 0 0 1 8.75 6");
}

.z9ia0ab0e {
  d: path("m6.5 15.5l2.75-2.75L12 15.5l2.75-2.75l2.75 2.75");
}

</style>
