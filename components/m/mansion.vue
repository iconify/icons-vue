<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gog8iv1cc"/><path class="btz3-54sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mansion" /></template>
<style>
.btz3-54sg {
  d: path("M10.5 21.5v-3.75a1.5 1.5 0 0 1 3 0v3.75m-1.5-11h.01M5.5 16h.01m12.99 0h.01");
}

.gog8iv1cc {
  d: path("M2.5 19.75v-6.5a1.75 1.75 0 0 1 1.75-1.75h2.5A1.75 1.75 0 0 0 8.5 9.75V8.158a1.75 1.75 0 0 1 .433-1.153l1.75-2a1.75 1.75 0 0 1 2.634 0l1.75 2a1.75 1.75 0 0 1 .433 1.153V9.75a1.75 1.75 0 0 0 1.75 1.75h2.5a1.75 1.75 0 0 1 1.75 1.75v6.5a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
