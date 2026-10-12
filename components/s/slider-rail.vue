<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ijw_3dbge"/><path class="a7xbknbyy"/><path class="vje23xb_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:slider-rail" /></template>
<style>
.a7xbknbyy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.75h.01");
}

.ijw_3dbge {
  width: 10px;
  height: 6.5px;
  x: 7px;
  y: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.vje23xb_d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10v3.5m-9.25 0h18.5M6 18.5h12m-2-2l2 2l-2 2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
