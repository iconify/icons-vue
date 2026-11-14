<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xn5npbbjl"/><path class="fcspwobyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mint-julep" /></template>
<style>
.fcspwobyd {
  d: path("M14 8.25q.5-5.75 6-5.75q-.5 5.5-6 5.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xn5npbbjl {
  d: path("M6 10h12v9q0 2-2 2H8q-2 0-2-2Zm0 0q6-4 12 0");
}

</style>
