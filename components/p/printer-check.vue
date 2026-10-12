<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)"><path class="wlva369qy"/><rect class="fh5kqifur"/><path class="fmt7gtbnv"/></g><path class="we-il_b1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:printer-check" /></template>
<style>
.fh5kqifur {
  width: 10.5px;
  height: 8px;
  x: 6.75px;
  y: 13.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.fmt7gtbnv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 11h.01");
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.we-il_b1m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.75 17.75l1.75 1.75l3.5-3.75");
}

.wlva369qy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 17.25h-1.5a2.5 2.5 0 0 1-2.5-2.5v-4.5a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v4.5a2.5 2.5 0 0 1-2.5 2.5h-1.5m-10.5-9.5v-3a2 2 0 0 1 2-2h6.5a2 2 0 0 1 2 2v3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
