<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="evcs9qols"/><path class="goa6xmsjx"/><circle class="evze8sb2n"/><path class="jsqqbh54i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pedal-effect" /></template>
<style>
.evcs9qols {
  width: 14.5px;
  height: 14.5px;
  x: 4.75px;
  y: 6.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.evze8sb2n {
  cx: 12px;
  cy: 16.25px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.goa6xmsjx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01m5.99 0h.01");
}

.jsqqbh54i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.75v-4m7 4v-4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
