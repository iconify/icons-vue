<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="hufrlzpcu"/><path class="xi-q60bju"/><path class="jrhd20qrl"/><path class="hnpg40b2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:on-screen-keyboard" /></template>
<style>
.hnpg40b2w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 16.75h7");
}

.hufrlzpcu {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.jrhd20qrl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 13.5h.01m3.49 0h.01m3.99 0h.01m3.49 0h.01");
}

.xi-q60bju {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.5h18.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
