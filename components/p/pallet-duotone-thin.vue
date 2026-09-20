<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rbrrfcbln"/><path class="at_623xyx"/><path class="ys-dg812g"/><path class="jkuojibnm"/><path class="fmlaifbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pallet-duotone-thin" /></template>
<style>
.at_623xyx {
  d: path("M5 6a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.fmlaifbpn {
  d: path("M12 16v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.rbrrfcbln {
  fill: currentColor;
  d: path("M5 6a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
