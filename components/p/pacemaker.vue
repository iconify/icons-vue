<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bpitecb4m"/><path class="lja2rfb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pacemaker" /></template>
<style>
.bpitecb4m {
  d: path("M8.5 8za6 6 0 0 1 6 6a6 6 0 0 1-6 6a6 6 0 0 1-6-6a6 6 0 0 1 6-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lja2rfb8l {
  d: path("M4.75 14h2l1-2l1.75 4l1-2h1.75m1-4.75C14.5 5.5 17.5 3 20 4.25c2 1 1 4.25-1.5 4.25c-2 0-1.75-2.5 0-2.25");
}

</style>
