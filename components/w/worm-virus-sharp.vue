<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="qdmx2ybjp"/><circle class="ggghabc2u"/><circle class="nkapmrh1q"/><path class="v90ywdids"/><path class="f8fsgqbje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:worm-virus-sharp" /></template>
<style>
.f8fsgqbje {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.66 4.82L15 2.75m3.7 2.88l1.55-1.38");
}

.ggghabc2u {
  cx: 10.9px;
  cy: 13.1px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nkapmrh1q {
  cx: 16.6px;
  cy: 7.4px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qdmx2ybjp {
  cx: 5.25px;
  cy: 18.75px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v90ywdids {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.6 7.4h.01");
}

</style>
