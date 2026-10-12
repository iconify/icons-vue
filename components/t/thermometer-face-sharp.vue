<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="iazhrbmsr"/><path class="goa6xmsjx"/><path class="p-kb37bdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thermometer-face-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.goa6xmsjx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01m5.99 0h.01");
}

.iazhrbmsr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 8l2.5-.75m7 .75l-2.5-.75");
}

.p-kb37bdi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.49 15.64l5 2.25l1.161.461l1.02-2.28l-1.161-.461l-5-2.25l-1.161-.461l-1.02 2.28z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
