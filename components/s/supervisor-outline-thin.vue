<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d-tnphbnb"/><path class="mq1k2k45m"/><path class="i8t3_pbsa"/><path class="cuxt49b2j"/><path class="vs9lv0b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:supervisor-outline-thin" /></template>
<style>
.cuxt49b2j {
  d: path("m9.5 10.5 -2 2");
}

.d-tnphbnb {
  d: path("M13.27 5.28a3 3 0 1 1 -2.54 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8t3_pbsa {
  d: path("M20.27 12.28a3 3 0 1 1 -2.54 0");
}

.mq1k2k45m {
  d: path("M6.27 12.28a3 3 0 1 1 -2.54 0");
}

.vs9lv0b4s {
  d: path("m14.5 10.5 2 2");
}

</style>
