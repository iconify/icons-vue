<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4r6-jx3t"/><path class="re96flbpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:workbook" /></template>
<style>
.f4r6-jx3t {
  d: path("M12 6.25c-2.5-2-6-2.5-9.25-1.5v14c3.25-1 6.75-.5 9.25 1.5c2.5-2 6-2.5 9.25-1.5v-14c-3.25-1-6.75-.5-9.25 1.5m0 0v14M5.5 9.75h3.75m-3.75 3.5h3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.re96flbpo {
  d: path("m14.5 11.5l1.75 1.75l3-3.5");
}

</style>
