<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="o6y4byb0b"/><path class="q_nfnc6mi"/><path class="kkbr-cbdl"/><rect class="bxsfpr4nx"/><path class="a22z11bec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:private-key" /></template>
<style>
.a22z11bec {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.75 5.75v-1a1.75 1.75 0 0 1 3.5 0v1");
}

.bxsfpr4nx {
  width: 7.25px;
  height: 5.75px;
  x: 14px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.kkbr-cbdl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 15h10M19 15v3m-2.75-3v2.25");
}

.o6y4byb0b {
  cx: 7px;
  cy: 15px;
  r: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q_nfnc6mi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
