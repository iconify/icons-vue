<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="hwsal5q-o"/><path class="ws3khsbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sphere" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hwsal5q-o {
  cx: 12px;
  cy: 12px;
  r: 8px;
}

.ws3khsbra {
  d: path("M6.83 10.12a5.5 5.5 0 0 1 3.29-3.29");
}

</style>
