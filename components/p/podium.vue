<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wn7d8hb0m"/><path class="sn2fxebfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:podium" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sn2fxebfr {
  d: path("m11 9l1.25-1v5.25");
}

.wn7d8hb0m {
  d: path("M2.75 21.25V12.5a1 1 0 0 1 1-1h5V5.75a1 1 0 0 1 1-1h4.5a1 1 0 0 1 1 1v8H20a1 1 0 0 1 1 1v6.5Z");
}

</style>
