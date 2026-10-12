<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="seka57b3v"/><rect class="a0fde9buh"/><rect class="moshw3vqk"/><path class="obcntljhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-camera" /></template>
<style>
.a0fde9buh {
  width: 14px;
  height: 10.5px;
  x: 2.75px;
  y: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.moshw3vqk {
  width: 4.5px;
  height: 6.5px;
  x: 16.75px;
  y: 10.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.obcntljhj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 12.5h.01");
}

.seka57b3v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 8.75v-2.5a1.5 1.5 0 0 1 1.5-1.5h6a1.5 1.5 0 0 1 1.5 1.5v2.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
