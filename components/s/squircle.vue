<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="curaqsq-h"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:squircle" /></template>
<style>
.curaqsq-h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c7.4 0 9.25 1.85 9.25 9.25S19.4 21.25 12 21.25S2.75 19.4 2.75 12S4.6 2.75 12 2.75");
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

</style>
