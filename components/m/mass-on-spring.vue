<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vbq99qh3p"/><path class="io5_9ob7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mass-on-spring" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.io5_9ob7b {
  d: path("M9.726 16h4.548a1.75 1.75 0 0 1 1.645 1.152l.727 2a1.75 1.75 0 0 1-1.644 2.348H8.998a1.75 1.75 0 0 1-1.644-2.348l.727-2A1.75 1.75 0 0 1 9.726 16");
}

.vbq99qh3p {
  d: path("M6 2.5h12m-6 0v2l3.5 1.75l-7 3.25l7 3.25L12 14.5V16");
}

</style>
