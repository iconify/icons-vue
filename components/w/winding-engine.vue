<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ouyv6nm-c"/><path class="aopd0wbsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:winding-engine" /></template>
<style>
.aopd0wbsp {
  d: path("M7.5 9.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8 0V18a2.5 2.5 0 0 0 5 0v-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ouyv6nm-c {
  d: path("M2.5 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0M9 16v5m-5.5 0H14");
}

</style>
