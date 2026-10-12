<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="qph70qsph"/><rect class="shwjf0bny"/><path class="gxbuc2gda"/><path class="yxc5crkal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mesh-router" /></template>
<style>
.gxbuc2gda {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 17.25h.01m10.99 0h.01");
}

.qph70qsph {
  width: 6.5px;
  height: 12px;
  x: 3.25px;
  y: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3.25px;
}

.shwjf0bny {
  width: 6.5px;
  height: 12px;
  x: 14.25px;
  y: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3.25px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yxc5crkal {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 7.5a3.5 3.5 0 0 1 4.5 0m-6.5-2.75a6.5 6.5 0 0 1 8.5 0");
}

</style>
