<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-5azvl3z"/><path class="rffc6mmne"/><path class="rferrcchp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shipping-label-print" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rferrcchp {
  d: path("M8.5 14h7a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 19v-3.5A1.5 1.5 0 0 1 8.5 14");
}

.rffc6mmne {
  d: path("M7 9h10a3.5 3.5 0 0 1 3.5 3.5v2A3.5 3.5 0 0 1 17 18H7a3.5 3.5 0 0 1-3.5-3.5v-2A3.5 3.5 0 0 1 7 9");
}

.z-5azvl3z {
  d: path("M8.75 3.5h6.5A1.75 1.75 0 0 1 17 5.25v4.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 9.75v-4.5A1.75 1.75 0 0 1 8.75 3.5");
}

</style>
