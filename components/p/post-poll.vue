<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><path class="g67wtabwr"/><path class="lmcw2zq3s"/><path class="s96vgdble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:post-poll" /></template>
<style>
.aqmj_4big {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.g67wtabwr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 8H14");
}

.lmcw2zq3s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.75 8l1 1l2-2");
}

.s96vgdble {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 12h5m-5 4H9");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
