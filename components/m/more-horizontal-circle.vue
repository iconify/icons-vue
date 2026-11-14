<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="tumim4b_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:more-horizontal-circle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.tumim4b_r {
  d: path("M7 12a.75.75 0 1 0 1.5 0A.75.75 0 1 0 7 12m4.25 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m4.25 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

</style>
