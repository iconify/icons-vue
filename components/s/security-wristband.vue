<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tyz9vfbsp"/><path class="dxooo_bis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-wristband" /></template>
<style>
.dxooo_bis {
  d: path("M2.5 9.75a9.5 3.5 0 0 0 4 2.75m11 0a9.5 3.5 0 0 0 4-2.75m-12.375 1h5.75a2.625 2.625 0 0 1 2.625 2.625v1.5a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 6.5 14.875v-1.5a2.625 2.625 0 0 1 2.625-2.625");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tyz9vfbsp {
  d: path("M6.5 16.5a9.5 3.5 0 0 1-4-2.75v-4a9.5 3.5 0 0 1 19 0v4a9.5 3.5 0 0 1-4 2.75");
}

</style>
