<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dwuku1b8h"/><path class="l4o99bcpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pharmacy-basket" /></template>
<style>
.dwuku1b8h {
  d: path("M4.839 12h14.322a1.75 1.75 0 0 1 1.679 2.244l-1.471 5a1.75 1.75 0 0 1-1.678 1.256H6.309a1.75 1.75 0 0 1-1.678-1.256l-1.471-5A1.75 1.75 0 0 1 4.839 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4o99bcpv {
  d: path("M3.75 12a4.25 4.25 0 0 1 8.5 0M15 12V8.5A1.5 1.5 0 0 1 16.5 7h2A1.5 1.5 0 0 1 20 8.5V12m-2.75-8.5h.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5V5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
