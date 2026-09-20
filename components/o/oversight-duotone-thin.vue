<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dktry7bqc"/><path class="irgposbpi"/><path class="atzzdxr0g"/><path class="c3srb1iyw"/><path class="ykru-q-7x"/><path class="bo51iypxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:oversight-duotone-thin" /></template>
<style>
.atzzdxr0g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 13.26a8 8 0 0 1 15.04 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.c3srb1iyw {
  d: path("M19.5 10.74a8 8 0 0 1 -15.04 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irgposbpi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.5 10.74a8 8 0 0 1 -15.04 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ykru-q-7x {
  d: path("M4.5 13.26a8 8 0 0 1 15.04 0");
}

</style>
