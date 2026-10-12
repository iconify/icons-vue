<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="pwcz0tb2n"/><path class="nfs3xabro"/><path class="zeh16hb8v"/><path class="oteb36arp"/><path class="fxhu6xblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:order-tracking" /></template>
<style>
.fxhu6xblw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 7h.01");
}

.nfs3xabro {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11.75v3h3v-3");
}

.oteb36arp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 14.25s-4.25-3.9-4.25-7.25a4.25 4.25 0 0 1 8.5 0c0 3.35-4.25 7.25-4.25 7.25");
}

.pwcz0tb2n {
  width: 9.5px;
  height: 9.5px;
  x: 2.75px;
  y: 11.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zeh16hb8v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5 18.75h.01m3.24 0h.01");
}

</style>
