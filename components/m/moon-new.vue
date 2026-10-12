<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="s-q6e0b1m"/><path class="xefcbomhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-new" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s-q6e0b1m {
  cx: 10.5px;
  cy: 13.5px;
  r: 7.5px;
}

.xefcbomhk {
  d: path("M7.92 17.19a4.5 4.5 0 0 1 0-7.38M19 2.75q.27 1.98 2.25 2.25q-1.98.27-2.25 2.25q-.27-1.98-2.25-2.25q1.98-.27 2.25-2.25");
}

</style>
