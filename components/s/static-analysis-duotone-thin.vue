<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dktry7bqc"/><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="wl0lu-b8y"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="ashnowcpl"/><path class="bo51iypxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:static-analysis-duotone-thin" /></template>
<style>
.ashnowcpl {
  d: path("M7.3 10.29a5 5 0 0 1 9.4 0");
}

.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eh---ab1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.r1p5_ebae {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wl0lu-b8y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.3 10.29a5 5 0 0 1 9.4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
