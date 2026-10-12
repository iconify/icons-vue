<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="fryq0r-dv"/><path class="h8yydcbka"/><path class="mh32_mbuf"/><path class="jm65bxmpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:modem" /></template>
<style>
.fryq0r-dv {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.h8yydcbka {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 17.25v2.5m11.5-2.5v2.5m-2-11v-3.5a2.5 2.5 0 0 1 2.5-2.5h3");
}

.jm65bxmpq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 13h1.5");
}

.mh32_mbuf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 13h.01m2.99 0h.01m2.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
