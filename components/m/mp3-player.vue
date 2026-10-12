<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="gtu1mocoa"/><path class="rexr0p25v"/><circle class="biq2jjb5i"/><path class="tb6q2fbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mp3-player" /></template>
<style>
.biq2jjb5i {
  cx: 12px;
  cy: 15.75px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.gtu1mocoa {
  width: 12.5px;
  height: 18.5px;
  x: 5.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.rexr0p25v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.75h4.5a1 1 0 0 1 1 1v2.5a1 1 0 0 1-1 1h-4.5a1 1 0 0 1-1-1v-2.5a1 1 0 0 1 1-1");
}

.tb6q2fbtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
