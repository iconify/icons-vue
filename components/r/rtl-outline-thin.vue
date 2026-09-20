<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgrfb-bqu"/><path class="d8abqfbpc"/><path class="h-tbmj14o"/><path class="ltkkdtbvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rtl-outline-thin" /></template>
<style>
.d8abqfbpc {
  d: path("M3 11h18");
}

.h-tbmj14o {
  d: path("M6 17h15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ltkkdtbvf {
  d: path("M8.5 14.5 6 17l2.5 2.5");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
