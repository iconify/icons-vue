<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lv9nxeavm"/><path class="b23exnb-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:volley-kick" /></template>
<style>
.b23exnb-t {
  d: path("M13.25 8.75q3.75-2.25 7.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lv9nxeavm {
  d: path("M4 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 5.25l1 4.25l-2 7m2-7l5 1.75l2-2.75M13 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
