<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="rogdlcbqf"/><path class="p2pcalb3f"/><path class="pvh7ewp6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:otp-code" /></template>
<style>
.p2pcalb3f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 12h.01m3.49 0h.01m3.49 0h.01m3.49 0h.01");
}

.pvh7ewp6v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 18.25h3");
}

.rogdlcbqf {
  width: 15px;
  height: 18.5px;
  x: 4.5px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.75px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
