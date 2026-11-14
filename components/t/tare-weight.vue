<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="apkup8b8d"/><path class="plksdhbjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tare-weight" /></template>
<style>
.apkup8b8d {
  d: path("M6.5 3h11c0 3-1.5 5.25-3.5 6h-4c-2-.75-3.5-3-3.5-6M4 9h16m-8 0v2.75m-5.359 0h10.718a2.625 2.625 0 0 1 2.571 2.098l.923 4.5a2.625 2.625 0 0 1-2.571 3.152H5.718a2.625 2.625 0 0 1-2.571-3.152l.923-4.5a2.625 2.625 0 0 1 2.571-2.098");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.plksdhbjo {
  d: path("M10 16.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
