<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="j6e8ysbiz"/><rect class="khyfbfb5l"/><path class="q1g4j3b4q"/><path class="kr9hw9brb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wallet-cards" /></template>
<style>
.j6e8ysbiz {
  width: 12.5px;
  height: 4.5px;
  x: 5.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.khyfbfb5l {
  width: 18.5px;
  height: 14px;
  x: 2.75px;
  y: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.kr9hw9brb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.9 14.25h.01");
}

.q1g4j3b4q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 11.5h4.5V17h-4.5a2.75 2.75 0 0 1 0-5.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
