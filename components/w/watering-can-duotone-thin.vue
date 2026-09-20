<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vq-1y2cme"/><path class="dwnj8ebpv"/><path class="kkard_6ho"/><path class="lm2p_gfvh"/><path class="j6kp_yter"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:watering-can-duotone-thin" /></template>
<style>
.dwnj8ebpv {
  d: path("M6 10v10h10V10Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6kp_yter {
  d: path("M8 10c0 -4 6 -4 6 0");
}

.kkard_6ho {
  d: path("m16 12 5 -5");
}

.lm2p_gfvh {
  d: path("m19 5 3 3");
}

.vq-1y2cme {
  fill: currentColor;
  d: path("M6 10v10h10V10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
