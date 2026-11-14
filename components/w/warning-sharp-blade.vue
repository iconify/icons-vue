<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k35tnqbpx"/><path class="wc1pm8b5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warning-sharp-blade" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k35tnqbpx {
  d: path("m14.322 6.899l5.146 9.751a2.625 2.625 0 0 1-2.322 3.85H6.854a2.625 2.625 0 0 1-2.322-3.85l5.146-9.751a2.625 2.625 0 0 1 4.644 0");
}

.wc1pm8b5h {
  d: path("M10.5 18v-7.5c2.5 1.75 3.25 4 3.25 7.5Z");
}

</style>
