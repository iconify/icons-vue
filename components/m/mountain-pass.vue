<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d002cybsu"/><path class="cc5_z8btn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mountain-pass" /></template>
<style>
.cc5_z8btn {
  d: path("m6.75 11.5l1.5.75l1.5-.75l1.5.75m1.5-.5L16 8l5.25 12.25H18.5");
}

.d002cybsu {
  d: path("m9.56 5.87l6.63 13.26q.56 1.12-.69 1.12H4q-1.25 0-.78-1.16L8.53 5.91Q9 4.75 9.56 5.87");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
