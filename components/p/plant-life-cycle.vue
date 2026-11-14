<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="svdabmlfc"/><path class="puw_r9ilr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-life-cycle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.puw_r9ilr {
  d: path("m6 8.25l.25-3l-3-.25M12 17v-4c-.25-2.5-2-4-4.5-4c0 2.25 1.75 4 4.5 4c.25-2.75 2-4.5 4.5-4.5c0 2.5-1.75 4.5-4.5 4.5");
}

.svdabmlfc {
  d: path("M17.75 5.25a9 9 0 1 1-11.5 0");
}

</style>
