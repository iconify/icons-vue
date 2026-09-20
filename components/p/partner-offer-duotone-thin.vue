<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="unu7n2b0o"/><path class="n2wmvdxwf"/><path class="xpzpcfrzo"/><path class="gzn3b0b7u"/><path class="pywr_yykw"/><path class="m0hvambgh"/><path class="v4hdeje_n"/><path class="bje48wbgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:partner-offer-duotone-thin" /></template>
<style>
.bje48wbgy {
  d: path("M11.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gzn3b0b7u {
  fill: currentColor;
  d: path("M11.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.m0hvambgh {
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n2wmvdxwf {
  fill: currentColor;
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pywr_yykw {
  d: path("m4 12 8 -8h8v8l-8 8Z");
}

.unu7n2b0o {
  fill: currentColor;
  d: path("m4 12 8 -8h8v8l-8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v4hdeje_n {
  d: path("M8.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xpzpcfrzo {
  fill: currentColor;
  d: path("M8.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
