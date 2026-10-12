<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="v3x3kdbao"/><path class="wmsa9dn-q"/><path class="kpgldhbxi"/><path class="id2a4xb9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tax-calculator" /></template>
<style>
.id2a4xb9m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 17.25h7.5");
}

.kpgldhbxi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 7.75h.01m5.49 5.5h.01");
}

.v3x3kdbao {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.wmsa9dn-q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.25 13.25l5.5-5.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
