<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hzfrtbyoc"/><path class="fuj8tt53e"/><path class="qom4v_bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:test-watch" /></template>
<style>
.fuj8tt53e {
  d: path("M6 10c1.5-2.5 3.5-3.5 6-3.5s4.5 1 6 3.5c-1.5 2.5-3.5 3.5-6 3.5s-4.5-1-6-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hzfrtbyoc {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 18 17H6a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 6 3m6 14v4m-3.5 0h7");
}

.qom4v_bvt {
  fill: currentColor;
  d: path("M10.5 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
