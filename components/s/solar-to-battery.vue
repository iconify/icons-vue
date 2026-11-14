<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zccv1yncn"/><path class="ls9lz-b6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solar-to-battery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ls9lz-b6q {
  d: path("M13.5 5.5H17a2 2 0 0 1 2 2V12m-2-2l2 2l2-2");
}

.zccv1yncn {
  d: path("M5.771 2.5h6.458a1.5 1.5 0 0 1 1.48 1.747l-.5 3a1.5 1.5 0 0 1-1.48 1.253H5.271a1.5 1.5 0 0 1-1.48-1.747l.5-3A1.5 1.5 0 0 1 5.771 2.5M7.125 15h8.75a2.625 2.625 0 0 1 2.625 2.625v1.25a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 4.5 18.875v-1.25A2.625 2.625 0 0 1 7.125 15M18.5 16.75h1a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1h-1M9.25 2.5l-1 6M4 5.5h9.5");
}

</style>
