<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kvq1zbcqb"/><path class="io_87lbji"/><circle class="f90gk5b2m"/><path class="et2_-pbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:url-scan" /></template>
<style>
.et2_-pbzq {
  d: path("m13.5 18.75l2.5 2.5");
}

.f90gk5b2m {
  cx: 11px;
  cy: 16.25px;
  r: 3.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.io_87lbji {
  d: path("m6.75 8.25l1.5-3m1.25 3l1.5-3m1.75 1.5h5");
}

.kvq1zbcqb {
  width: 18.5px;
  height: 6px;
  x: 2.75px;
  y: 3.75px;
  rx: 3px;
}

</style>
