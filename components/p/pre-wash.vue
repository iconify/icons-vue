<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mfxiv8bdq"/><path class="omweahbog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pre-wash" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mfxiv8bdq {
  d: path("M3 11h18l-1.5 7.75a2 2 0 0 1-2 1.75h-11a2 2 0 0 1-2-1.75Zm5 0V6L5.5 7.5L4 5l4.5-2.5h7L20 5l-1.5 2.5L16 6v5");
}

.omweahbog {
  d: path("M7 15.5q1.75-1.5 3.5 0t3.5 0q1.5-1.25 3-.25");
}

</style>
