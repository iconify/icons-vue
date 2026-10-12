<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kvz5volay"/><path class="t0go0dbaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ufo" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvz5volay {
  d: path("M2.75 12a9.25 3.25 0 1 0 18.5 0a9.25 3.25 0 1 0-18.5 0");
}

.t0go0dbaf {
  d: path("M7.5 9.16a4.5 4.5 0 0 1 9 0a9.25 3.25 0 0 0-9 0m1 9.09l-1 3m4.5-3v3m3.5-3l1 3");
}

</style>
