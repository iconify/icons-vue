<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f2qykebex"/><path class="by8f9v1yj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ram-check" /></template>
<style>
.by8f9v1yj {
  d: path("m9.5 10.5l1.75 1.75L15 8.5");
}

.f2qykebex {
  d: path("M4.625 6.5h14.75A2.625 2.625 0 0 1 22 9.125v3.75a2.625 2.625 0 0 1-2.625 2.625H4.625A2.625 2.625 0 0 1 2 12.875v-3.75A2.625 2.625 0 0 1 4.625 6.5m.875 9v3m3-3v3m7-3v3m3-3v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
