<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ttns_mbbj"/><rect class="du-uqrwda"/><path class="mp7msgecv"/><path class="s9uyqacfh"/><path class="foqzl0b5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nightstand" /></template>
<style>
.du-uqrwda {
  width: 14.5px;
  height: 8px;
  x: 4.75px;
  y: 11.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.foqzl0b5k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 19.75v1.5m10-1.5v1.5");
}

.mp7msgecv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 15.75h14.5");
}

.s9uyqacfh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.75h.01m-.01 4h.01");
}

.ttns_mbbj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 2.75h2q.75 0 1 .71l1.25 3.58q.25.71-.5.71h-5.5q-.75 0-.5-.71L10 3.46q.25-.71 1-.71m1 5V11");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
