<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fizmkteml"/><path class="i4am83b3q"/><path class="h_2w94b4c"/><path class="j7phtvv5f"/><path class="p-74fg5cj"/><path class="vz5_16nyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:subscribe-duotone-thin" /></template>
<style>
.fizmkteml {
  fill: currentColor;
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h_2w94b4c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 6a13 13 0 0 1 13 13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4am83b3q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 12a7 7 0 0 1 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j7phtvv5f {
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.p-74fg5cj {
  d: path("M5 12a7 7 0 0 1 7 7");
}

.vz5_16nyg {
  d: path("M5 6a13 13 0 0 1 13 13");
}

</style>
