<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="jf60lda-p"/><path class="m_br3zqwz"/><path class="nbi0lcc_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:release-notes" /></template>
<style>
.jf60lda-p {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.m_br3zqwz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 6.75v2.5M6.5 8H9m2.75 0h4.5m-4.5 4h4.5m-4.5 4h2.5");
}

.nbi0lcc_d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 12h.01m-.01 4h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
