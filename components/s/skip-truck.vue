<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h9fy-7lsi"/><path class="ns6i8jbzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skip-truck" /></template>
<style>
.h9fy-7lsi {
  d: path("M15 16.5V9h3.5l3 3.5v4m-19 0h19M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ns6i8jbzc {
  d: path("M16 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M4.242 6.5h6.516a1.5 1.5 0 0 1 1.484 1.723l-1.05 7A1.5 1.5 0 0 1 9.708 16.5H5.292a1.5 1.5 0 0 1-1.484-1.277l-1.05-7A1.5 1.5 0 0 1 4.242 6.5");
}

</style>
