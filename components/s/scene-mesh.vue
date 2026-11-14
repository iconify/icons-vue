<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c2ii5983h"/><path class="xq0ikof0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scene-mesh" /></template>
<style>
.c2ii5983h {
  d: path("M4 8h10.5A1.5 1.5 0 0 1 16 9.5V20a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20V9.5A1.5 1.5 0 0 1 4 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xq0ikof0c {
  d: path("M2.5 8L8 2.5h13.5V16L16 21.5M16 8l5.5-5.5M2.5 8L16 21.5");
}

</style>
