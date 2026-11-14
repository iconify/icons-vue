<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l8fgk_-ug"/><path class="chjhd6b_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vacuum-filter" /></template>
<style>
.chjhd6b_k {
  d: path("M10.25 2.5h3.5a1.75 1.75 0 0 1 1.75 1.75v12.5a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75V4.25a1.75 1.75 0 0 1 1.75-1.75M8.5 7h7m-7 3.5h7m-7 3.5h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l8fgk_-ug {
  d: path("M5 4v15.5a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V4");
}

</style>
