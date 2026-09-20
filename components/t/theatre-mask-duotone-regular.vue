<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rbmibvv8s"/><path class="jlgxzd_ny"/><path class="rlk52sj8y"/><path class="h4ns5qbtt"/><path class="c4o3x9bhp"/><path class="a97qfmbix"/><path class="se9hxcxbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:theatre-mask-duotone-regular" /></template>
<style>
.a97qfmbix {
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.c4o3x9bhp {
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.h4ns5qbtt {
  d: path("M5 5h14v8a7 7 0 0 1 -14 0Z");
}

.jlgxzd_ny {
  fill: currentColor;
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rbmibvv8s {
  fill: currentColor;
  d: path("M5 5h14v8a7 7 0 0 1 -14 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rlk52sj8y {
  fill: currentColor;
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.se9hxcxbl {
  d: path("M16 13a4 4 0 0 1 -8 0");
}

</style>
