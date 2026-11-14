<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="yrdtzkbss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skip-back-circle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.yrdtzkbss {
  d: path("m13.14 10.152l-.885.619a1.5 1.5 0 0 0 0 2.458l.885.619a1.5 1.5 0 0 0 2.36-1.229v-1.238a1.5 1.5 0 0 0-2.36-1.229M8.5 8.5v7");
}

</style>
