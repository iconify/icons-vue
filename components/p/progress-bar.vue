<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h2q0ipbys"/><path class="uvc7znbru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:progress-bar" /></template>
<style>
.h2q0ipbys {
  d: path("M6 8h12a3.5 3.5 0 0 1 3.5 3.5v1A3.5 3.5 0 0 1 18 16H6a3.5 3.5 0 0 1-3.5-3.5v-1A3.5 3.5 0 0 1 6 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uvc7znbru {
  fill: currentColor;
  d: path("M6.5 10.5H13a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H6.5A1.5 1.5 0 0 1 5 12a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
