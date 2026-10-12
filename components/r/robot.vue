<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="pfc5ew1xi"/><path class="mwns-9bhm"/><path class="kqef4tbqv"/><path class="tcl_u7zhf"/><path class="ttxdcjbnj"/><path class="xnnknu4ij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:robot" /></template>
<style>
.kqef4tbqv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3.25h.01");
}

.mwns-9bhm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.75V4");
}

.pfc5ew1xi {
  width: 13.5px;
  height: 12.5px;
  x: 5.25px;
  y: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.tcl_u7zhf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5V16m18.5-3.5V16");
}

.ttxdcjbnj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 12.75h.01m5.49 0h.01");
}

.xnnknu4ij {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 16.5h4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
