<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vtgm4jbau"/><path class="h78w2kbwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wifi-calling" /></template>
<style>
.h78w2kbwr {
  d: path("M9.49 5.49a8.5 8.5 0 0 1 12.02 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vtgm4jbau {
  d: path("M4 7.5h3.25l1 3.5l-1.75 1.5c.75 2 3 4.25 5 5l1.5-1.75l3.5 1V20a1.5 1.5 0 0 1-1.5 1.5C8 21.5 2.5 16 2.5 9A1.5 1.5 0 0 1 4 7.5m9.732 2.232a2.5 2.5 0 0 1 3.536 0m-5.657-2.121a5.5 5.5 0 0 1 7.778 0");
}

</style>
