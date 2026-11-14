<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m9x8wjb3e"/><path class="qf-jp1b3x"/><path class="f7107y-lb"/><path class="losj4cmhy"/><path class="g3ycjzbfz"/><path class="tula0zr8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:route-copy" /></template>
<style>
.f7107y-lb {
  fill: currentColor;
  d: path("M8.5 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.g3ycjzbfz {
  d: path("M14 16v-5c0-3 4-3 4-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.losj4cmhy {
  d: path("M11.5 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.m9x8wjb3e {
  d: path("M3.5 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.qf-jp1b3x {
  d: path("M6 16v-5c0-3 4-3 4-6");
}

.tula0zr8i {
  fill: currentColor;
  d: path("M16.5 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
