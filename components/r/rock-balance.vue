<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="acgk1yoqa"/><path class="hlelexccp"/><path class="i7nnmtb6h"/><path class="vc7nt6b7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rock-balance" /></template>
<style>
.acgk1yoqa {
  d: path("M4.5 19.25a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0");
}

.hlelexccp {
  d: path("M8 13.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7nnmtb6h {
  d: path("M5 7.25a7 2 0 1 0 14 0a7 2 0 1 0-14 0");
}

.vc7nt6b7x {
  d: path("M9.5 3.75a2.5 1.5 0 1 0 5 0a2.5 1.5 0 1 0-5 0");
}

</style>
