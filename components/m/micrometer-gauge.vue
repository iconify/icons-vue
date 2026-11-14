<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="brzn_ippx"/><path class="hamztwb1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:micrometer-gauge" /></template>
<style>
.brzn_ippx {
  d: path("M3.5 5.5V13A5.5 5.5 0 0 0 9 18.5h6v-8M6.5 8H13");
}

.hamztwb1t {
  d: path("M14.75 5.5h4.5A1.75 1.75 0 0 1 21 7.25v1.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 13 8.75v-1.5a1.75 1.75 0 0 1 1.75-1.75m2.25 0v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
