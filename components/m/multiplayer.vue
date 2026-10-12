<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="a-mcl9b0v"/><circle class="l5ips3bsh"/><path class="lmhwys7-v"/><path class="rfhlbzqfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:multiplayer" /></template>
<style>
.a-mcl9b0v {
  cx: 7px;
  cy: 6px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5ips3bsh {
  cx: 17px;
  cy: 6px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmhwys7-v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 11h8.5a3.25 3.25 0 0 1 3.15 2.5l.8 4.3a2 2 0 0 1-3.45 1.75L14.5 17.5h-5l-2.25 2.05A2 2 0 0 1 3.8 17.8l.8-4.3A3.25 3.25 0 0 1 7.75 11");
}

.rfhlbzqfy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 14.5h.01m7.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
