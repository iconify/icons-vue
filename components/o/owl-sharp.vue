<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rt12wc7ip"/><circle class="ow0ax2vzz"/><circle class="dy1ykbc3u"/><path class="dd_6j-l0z"/><path class="dwiwgye5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:owl-sharp" /></template>
<style>
.dd_6j-l0z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11h.01M15 11h.01");
}

.dwiwgye5v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11 14.25l1 1.25l1-1.25m-3.5 4l1.25-.75l1.25.75l1.25-.75l1.25.75");
}

.dy1ykbc3u {
  cx: 15px;
  cy: 11px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ow0ax2vzz {
  cx: 9px;
  cy: 11px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rt12wc7ip {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3.75L8.5 6.5h7l3.75-2.75V14a7.25 7.25 0 0 1-14.5 0Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
