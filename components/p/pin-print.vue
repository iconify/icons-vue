<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzj_vg3lx"/><path class="zkdljcvlc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-print" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzj_vg3lx {
  d: path("M7 17H5.5a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H17v-3H7Zm0-9V4.5a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1V8");
}

.zkdljcvlc {
  d: path("M8.75 14h6.5A1.75 1.75 0 0 1 17 15.75v3a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 18.75v-3A1.75 1.75 0 0 1 8.75 14m.75 3.25h5");
}

</style>
