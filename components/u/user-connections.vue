<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wv5f_1brg"/><path class="r_2ezabni"/><circle class="nev2nabhe"/><path class="r632x-bni"/><circle class="f1cj5wo7i"/><path class="rnv32ac2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-connections" /></template>
<style>
.f1cj5wo7i {
  cx: 19.25px;
  cy: 15.25px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nev2nabhe {
  cx: 4.75px;
  cy: 15.25px;
  r: 2px;
}

.r_2ezabni {
  d: path("M9 12.75c0-1 1.35-1.75 3-1.75s3 .75 3 1.75");
}

.r632x-bni {
  d: path("M2.75 21.25V21c0-1 .9-1.5 2-1.5s2 .5 2 1.5v.25");
}

.rnv32ac2g {
  d: path("M17.25 21.25V21c0-1 .9-1.5 2-1.5s2 .5 2 1.5v.25");
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

</style>
