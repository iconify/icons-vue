<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c1ie6_sio"/><path class="fvglrsj0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:molecular-weight" /></template>
<style>
.c1ie6_sio {
  d: path("M11.908 17.5H3l2.5-10h9l1.067 4.269");
}

.fvglrsj0j {
  d: path("M7.75 5.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m6.75 11a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4 3.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-1-2.5l1.25 1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
