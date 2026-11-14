<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kdnuuccmw"/><path class="pxew7npbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thermograph" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdnuuccmw {
  d: path("M4.25 3h9.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-9.5A1.75 1.75 0 0 1 2.5 4.75A1.75 1.75 0 0 1 4.25 3M4 6.5v14h10v-14");
}

.pxew7npbr {
  d: path("m6.75 15l1.5-3.75l1.5 3.25l1.5-4m0 0l7.25-2.25m0-.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
