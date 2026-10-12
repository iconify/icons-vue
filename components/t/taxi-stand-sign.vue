<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><path class="v8ysr6bgj"/><path class="ff151fxpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:taxi-stand-sign" /></template>
<style>
.aqmj_4big {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.ff151fxpk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 13.75h.01m5.49 0h.01");
}

.v8ysr6bgj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16v-3.25l1.5-3.5h7l1.5 3.5V16Zm1 0v1.75M16 16v1.75m-5.5-11h3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
