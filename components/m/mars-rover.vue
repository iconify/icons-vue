<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="psr-oob6o"/><path class="gsv6p4tio"/><rect class="g98hocbtd"/><path class="hs3hiubkz"/><path class="f123brk0z"/><circle class="p6k37obuz"/><circle class="hs5razboj"/><circle class="hkf5sd0yi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mars-rover" /></template>
<style>
.f123brk0z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 16.5l3.5-3l3 3l3-3l3.5 3");
}

.g98hocbtd {
  width: 5.5px;
  height: 3px;
  x: 13px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

.gsv6p4tio {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 9.5V5.75M4.5 9.5L3 7.25m0 0h4.5");
}

.hkf5sd0yi {
  cx: 18.5px;
  cy: 18.75px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hs3hiubkz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 4.25h.01");
}

.hs5razboj {
  cx: 12px;
  cy: 18.75px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p6k37obuz {
  cx: 5.5px;
  cy: 18.75px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.psr-oob6o {
  width: 15px;
  height: 4px;
  x: 4.5px;
  y: 9.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
