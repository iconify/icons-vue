<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aic6yg3oj"/><path class="dh1u-bjgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-grid-reference" /></template>
<style>
.aic6yg3oj {
  d: path("m2.5 5.5l6-2l7 2l6-2v15l-6 2l-7-2l-6 2Zm6-2v15m7-13v15M2.5 12h19");
}

.dh1u-bjgp {
  fill: currentColor;
  d: path("M12 14.5za1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 12 17a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 12 14.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
