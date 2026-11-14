<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uxhqkvq2m"/><path class="bds_6obgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mediation" /></template>
<style>
.bds_6obgy {
  d: path("M11.5 9H19a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2v3l-3-3h-4.5a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uxhqkvq2m {
  d: path("M14.5 6.25V5a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2v2.75L6.75 12");
}

</style>
