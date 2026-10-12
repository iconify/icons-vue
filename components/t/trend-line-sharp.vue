<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vf_31rbpy"/><circle class="oaykpkziz"/><circle class="r06hrywvu"/><circle class="na2sa9bxh"/><path class="h3oaqj1lq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trend-line-sharp" /></template>
<style>
.h3oaqj1lq {
  d: path("M7.25 16.5L19.75 6");
}

.na2sa9bxh {
  cx: 15px;
  cy: 5.5px;
  r: 1.5px;
}

.oaykpkziz {
  cx: 7.5px;
  cy: 11.75px;
  r: 1.5px;
}

.r06hrywvu {
  cx: 15.75px;
  cy: 13.75px;
  r: 1.5px;
}

.vf_31rbpy {
  d: path("M3.75 3.75v16.5h16.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
