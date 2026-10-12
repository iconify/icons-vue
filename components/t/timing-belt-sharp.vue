<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="r2hqmbbrp"/><circle class="xjynbecfo"/><path class="ts9eagb1i"/><circle class="zkqnmjbsk"/><path class="njenmdbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timing-belt-sharp" /></template>
<style>
.njenmdbpf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 12h.01");
}

.r2hqmbbrp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 6.5h7.5a5.5 5.5 0 0 1 0 11h-7.5a5.5 5.5 0 0 1 0-11Z");
}

.ts9eagb1i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xjynbecfo {
  cx: 8.25px;
  cy: 12px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zkqnmjbsk {
  cx: 15.75px;
  cy: 12px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
