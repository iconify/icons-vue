<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dktry7bqc"/><path class="nowdsq6_v"/><path class="bkcnp6b8w"/><path class="fqwy_4bqb"/><path class="oegd6zb7w"/><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="bo51iypxr"/><path class="de_2l4bkn"/><path class="oe2rn1bbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pii-detect-duotone-thin" /></template>
<style>
.bkcnp6b8w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.de_2l4bkn {
  d: path("M7 12h3");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fqwy_4bqb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.moha5wbmp {
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
}

.nowdsq6_v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oe2rn1bbo {
  d: path("M14 12h3");
}

.oegd6zb7w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yix-58bnj {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
