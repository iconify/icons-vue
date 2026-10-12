<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ug09fsb7w"/><rect class="h87fhkb7h"/><path class="di5_j9b_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:street-food" /></template>
<style>
.di5_j9b_k {
  d: path("M7 18.5v2.75m10-2.75v2.75");
}

.h87fhkb7h {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 13.5px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ug09fsb7w {
  d: path("m3 8.5l1.75-4.75h14.5L21 8.5a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0m2.25 2.25v2.75m13.5-2.75v2.75");
}

</style>
