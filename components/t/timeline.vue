<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c6bmv3q-h"/><path class="eu7cf_5yt"/><path class="xh4rzib9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:timeline" /></template>
<style>
.c6bmv3q-h {
  d: path("M2.5 12h19");
}

.eu7cf_5yt {
  fill: currentColor;
  d: path("M5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xh4rzib9z {
  d: path("M4.75 3h4.5A1.75 1.75 0 0 1 11 4.75v.75a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 3 5.5v-.75A1.75 1.75 0 0 1 4.75 3m10 13.75h4.5A1.75 1.75 0 0 1 21 18.5v.75A1.75 1.75 0 0 1 19.25 21h-4.5A1.75 1.75 0 0 1 13 19.25v-.75a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
