<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0ur13bxj"/><path class="gx-sxsb_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oxygen-saturation" /></template>
<style>
.gx-sxsb_a {
  d: path("M8 15a2.25 2.25 0 1 0 4.5 0A2.25 2.25 0 1 0 8 15m5.75.25c0-1 .75-1.5 1.5-1.5s1.5.5 1.5 1.25c0 1-3 2.25-3 3.5h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0ur13bxj {
  d: path("M12 2.5c3.5 4.5 7 8 7 12c0 3.9-3.1 7-7 7s-7-3.1-7-7c0-4 3.5-7.5 7-12");
}

</style>
