<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u9wuy_bfq"/><path class="iflxnubtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sale-ribbon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iflxnubtr {
  d: path("m9 14.5l-2 7l5-3l5 3l-2-7");
}

.u9wuy_bfq {
  d: path("m12 2.75l3.5 1V12a3.5 3.5 0 0 1-7 0V3.75Z");
}

</style>
