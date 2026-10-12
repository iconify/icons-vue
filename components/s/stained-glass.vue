<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="na6r2ab0k"/><circle class="aj6v90bht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stained-glass" /></template>
<style>
.aj6v90bht {
  cx: 12px;
  cy: 9.75px;
  r: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.na6r2ab0k {
  d: path("M4.75 21.25V10a7.25 7.25 0 0 1 14.5 0v11.25Zm0-5.5h14.5m-7.25 0v5.5m-3.75-5.5v5.5m7.5-5.5v5.5");
}

</style>
