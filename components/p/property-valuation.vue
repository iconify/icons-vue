<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mydf-xbdj"/><path class="ztrnz5yjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:property-valuation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mydf-xbdj {
  d: path("M2.75 17V9.15q0-1 .77-1.64l4.96-4.12q.77-.64 1.54 0l4.96 4.12q.77.64.77 1.64V17q0 1-1 1h-11q-1 0-1-1");
}

.ztrnz5yjf {
  d: path("m11 21l3.5-3.75l2.5 2l4.25-5m-3.5 0h3.5v3.5");
}

</style>
