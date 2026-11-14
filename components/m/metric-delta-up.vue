<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y8-axtbiq"/><path class="i-c6dccrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:metric-delta-up" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-c6dccrj {
  d: path("M17 12h4.5");
}

.y8-axtbiq {
  fill: currentColor;
  d: path("M5.591 17h5.818a1.75 1.75 0 0 0 1.501-2.65l-2.909-4.849a1.75 1.75 0 0 0-3.002 0L4.09 14.35A1.75 1.75 0 0 0 5.591 17");
}

</style>
