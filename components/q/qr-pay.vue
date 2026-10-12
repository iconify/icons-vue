<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="jog0cvb4h"/><rect class="euzx67hrw"/><rect class="c_m5u3brr"/><path class="pegcclbmn"/><circle class="ytfrt8b4j"/><path class="t-f4-ze4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:qr-pay" /></template>
<style>
.c_m5u3brr {
  width: 7px;
  height: 7px;
  x: 3.25px;
  y: 13.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.euzx67hrw {
  width: 7px;
  height: 7px;
  x: 13.75px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.jog0cvb4h {
  width: 7px;
  height: 7px;
  x: 3.25px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.pegcclbmn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 6.75h.01m10.49 0h.01M6.75 17.25h.01");
}

.t-f4-ze4h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.75 17.25l1 1l2-2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ytfrt8b4j {
  cx: 17.25px;
  cy: 17.25px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
