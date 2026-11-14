<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgwaycb7x"/><path class="isbi11mij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reagent-kit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isbi11mij {
  d: path("M5 3.5h5.5M6 3.5v12.75a1.75 1.75 0 0 0 3.5 0V3.5m4 2.5H19m-4.5 0v10.25a1.75 1.75 0 0 0 3.5 0V6");
}

.xgwaycb7x {
  d: path("M2.5 10v9.5a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2V10");
}

</style>
