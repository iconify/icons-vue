<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqu1-obmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:orchestra-pit" /></template>
<style>
.hqu1-obmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.625 2.5h6.75A2.625 2.625 0 0 1 18 5.125v3.75a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 6 8.875v-3.75A2.625 2.625 0 0 1 8.625 2.5m3.375 9v7m-4 0l4-3l4 3m-13.5 3h19M9 5.5h6m-6 3h4");
}

</style>
