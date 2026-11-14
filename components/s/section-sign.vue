<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lvmmffbxh"/><path class="wd4u1ln4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:section-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lvmmffbxh {
  d: path("M15.25 5.25c-.65-1-1.75-1.5-3.25-1.5c-1.9 0-3.25.95-3.25 2.5c0 3.25 6.5 3.25 6.5 7c0 1.35-1 2.35-2.5 2.75");
}

.wd4u1ln4i {
  d: path("M8.75 18.75c.65 1 1.75 1.5 3.25 1.5c1.9 0 3.25-.95 3.25-2.5c0-3.25-6.5-3.25-6.5-7c0-1.35 1-2.35 2.5-2.75");
}

</style>
