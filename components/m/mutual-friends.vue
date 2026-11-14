<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="znsj7bbfr"/><path class="f3v_s9bsz"/><path class="r5cjekb_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mutual-friends" /></template>
<style>
.f3v_s9bsz {
  d: path("M10.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M3 20.5C3 17.25 5.75 15 9.5 15s6.5 2.25 6.5 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5cjekb_s {
  d: path("M8 20.5c0-3.25 2.75-5.5 6.5-5.5s6.5 2.25 6.5 5.5");
}

.znsj7bbfr {
  d: path("M5.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
