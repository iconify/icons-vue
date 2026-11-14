<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="lfl78e0zg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:release-notes" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfl78e0zg {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-10.75-3h1.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 10.25 8h-1.5A1.25 1.25 0 0 1 7.5 6.75A1.25 1.25 0 0 1 8.75 5.5M8 11.75h.01m2.74 0H16m-8 3.5h.01m2.74 0H16m-8 3.5h.01m2.74 0H14");
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
