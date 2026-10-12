<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ehg7s0b4a"/><circle class="r8335-baj"/><path class="fq8fayugl"/><path class="rcbqokfet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:monopod" /></template>
<style>
.ehg7s0b4a {
  width: 14.5px;
  height: 9px;
  x: 4.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.fq8fayugl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 5.25h.01");
}

.r8335-baj {
  cx: 12px;
  cy: 7.25px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rcbqokfet {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.75v7.75m-3 1.75l3-1.75l3 1.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
