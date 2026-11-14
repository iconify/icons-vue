<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1g82abza"/><path class="q6e0agblr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roll-in-shower" /></template>
<style>
.g1g82abza {
  d: path("M2.5 3.5H7a2 2 0 0 1 2 2V8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q6e0agblr {
  d: path("M5 12a4 4 0 0 1 8 0Zm1.5 2.5l-1 4m3.5-4v4m2.5-4L12 18m4.75-4.75h.01m-.26 2.5v2.75h3l1.5 3m-6.25-3a2.5 2.5 0 0 0 3.25 3");
}

</style>
