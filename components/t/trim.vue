<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="eqlwhw62y"/><path class="la9inmbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trim" /></template>
<style>
.eqlwhw62y {
  width: 18.5px;
  height: 8px;
  x: 2.75px;
  y: 8px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.la9inmbxz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.75 10h.01M12 10h.01m7.24 0h.01M4.75 14h.01M12 14h.01m7.24 0h.01M8 5.25v13.5m8-13.5v13.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
