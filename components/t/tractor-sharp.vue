<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="evy479b8s"/><path class="sgbu95bxs"/><circle class="n2dc2ktde"/><path class="efa6jaccc"/><circle class="xw30-oz_l"/><path class="pr2iyxt7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tractor-sharp" /></template>
<style>
.efa6jaccc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 17.25h.01");
}

.evy479b8s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 11V4.5h7.067l.163.8l1.02 5.45h8.5v6h-7.5V11Z");
}

.n2dc2ktde {
  cx: 7.25px;
  cy: 17.25px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pr2iyxt7r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 19h.01");
}

.sgbu95bxs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4.5v4.25h5.4m3.6 2V7");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xw30-oz_l {
  cx: 18px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
