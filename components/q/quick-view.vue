<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="lo_lt5b5d"/><path class="z93kgtucg"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quick-view" /></template>
<style>
.lo_lt5b5d {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z93kgtucg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12C8 9.5 10 8.25 12 8.25S16 9.5 17.5 12C16 14.5 14 15.75 12 15.75S8 14.5 6.5 12");
}

</style>
