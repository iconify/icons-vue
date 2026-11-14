<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frobozbyt"/><path class="w9ho0yb9i"/><path class="e0g1ktb3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shape-exclude" /></template>
<style>
.e0g1ktb3q {
  d: path("M10.5 9h3a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 13.5v-3A1.5 1.5 0 0 1 10.5 9");
}

.frobozbyt {
  d: path("M7.375 3h3.25A4.375 4.375 0 0 1 15 7.375v3.25A4.375 4.375 0 0 1 10.625 15h-3.25A4.375 4.375 0 0 1 3 10.625v-3.25A4.375 4.375 0 0 1 7.375 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w9ho0yb9i {
  d: path("M13.375 9h3.25A4.375 4.375 0 0 1 21 13.375v3.25A4.375 4.375 0 0 1 16.625 21h-3.25A4.375 4.375 0 0 1 9 16.625v-3.25A4.375 4.375 0 0 1 13.375 9");
}

</style>
