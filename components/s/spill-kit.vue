<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i4evr3bpt"/><path class="nx11af0jy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spill-kit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4evr3bpt {
  d: path("M5.625 8h12.75A2.625 2.625 0 0 1 21 10.625v8.25a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-8.25A2.625 2.625 0 0 1 5.625 8M9 8V5.5A1.5 1.5 0 0 1 10.5 4h3A1.5 1.5 0 0 1 15 5.5V8M3 11h18");
}

.nx11af0jy {
  d: path("M12 13.25C13.25 15 14 16 14 17a2 2 0 0 1-4 0c0-1 .75-2 2-3.75");
}

</style>
