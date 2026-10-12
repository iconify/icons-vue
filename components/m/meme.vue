<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><path class="hqze38a6p"/><path class="h4e08zb4z"/><path class="qfnbw8big"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meme" /></template>
<style>
.aqmj_4big {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.h4e08zb4z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 13.5l2.75-2.75l2 2l2.25-2.25l3 3");
}

.hqze38a6p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 6.75h9");
}

.qfnbw8big {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17.25h10");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
