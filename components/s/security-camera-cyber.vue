<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="g2eyyjf0x"/><path class="sci58wslm"/><path class="q_o31nbqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:security-camera-cyber" /></template>
<style>
.g2eyyjf0x {
  width: 12.5px;
  height: 6.5px;
  x: 2.75px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.q_o31nbqr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12.25V17H4.75m0-2.25v4.5M18 7.25a2.5 2.5 0 0 1 0 3.5m1.75-5.25a5 5 0 0 1 0 7");
}

.sci58wslm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
