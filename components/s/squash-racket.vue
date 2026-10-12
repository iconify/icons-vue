<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gr_d7wb8g"/><path class="k10f36bcw"/><circle class="r159tcbbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:squash-racket" /></template>
<style>
.gr_d7wb8g {
  d: path("M7.5 2.75a3.5 5 0 1 0 0 10a3.5 5 0 1 0 0-10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k10f36bcw {
  d: path("m5.25 11.6l2.25 3.9l2.25-3.9M7.5 15.5v5.75M21.25 9v12.25m-3.75-3.5h3.75");
}

.r159tcbbe {
  cx: 16.25px;
  cy: 12px;
  r: 1.75px;
}

</style>
