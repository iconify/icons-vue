<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bic679bks"/><path class="xrg1pyeax"/><path class="yh3n9ccbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:queue-position" /></template>
<style>
.bic679bks {
  d: path("M10.5 3.5h9A1.5 1.5 0 0 1 21 5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 9 5a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xrg1pyeax {
  fill: currentColor;
  d: path("M10.5 10.5h9A1.5 1.5 0 0 1 21 12a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 9 12a1.5 1.5 0 0 1 1.5-1.5");
}

.yh3n9ccbi {
  d: path("M10.5 17.5h9A1.5 1.5 0 0 1 21 19a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 9 19a1.5 1.5 0 0 1 1.5-1.5M3 9.5L5.5 12L3 14.5");
}

</style>
