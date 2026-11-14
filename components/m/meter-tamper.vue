<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bhq0e5b8p"/><path class="tc-mywesd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meter-tamper" /></template>
<style>
.bhq0e5b8p {
  d: path("M2.5 10.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tc-mywesd {
  d: path("M9 6h3a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 12 9H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 6m1.5 9l2.25-2.75m7.75 2.25V18m0 3h.01");
}

</style>
