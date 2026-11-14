<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dsleywj5l"/><path class="gxaivubom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spade-suit" /></template>
<style>
.dsleywj5l {
  d: path("m12 2.5l-8 8.25a4.75 4.75 0 1 0 8 4.75a4.75 4.75 0 1 0 8-4.75Z");
}

.gxaivubom {
  d: path("m13.375 17.75l.493 1.166A1.5 1.5 0 0 1 12.487 21h-.974a1.5 1.5 0 0 1-1.381-2.084l.493-1.166a1.493 1.493 0 0 1 2.75 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
