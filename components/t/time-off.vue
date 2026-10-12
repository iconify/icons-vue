<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xglklabzt"/><path class="ngayx2bsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ngayx2bsa {
  d: path("M12 7.5V12H8.5M3.75 3.75l16.5 16.5");
}

.xglklabzt {
  cx: 12px;
  cy: 12px;
  r: 8.5px;
}

</style>
