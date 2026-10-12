<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="qepuaqbvx"><path class="kqezffzhk"/><path class="qwn4--teq"/><path class="va-cqqbhp"/></g><path class="upeuobe7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:server-x-sharp" /></template>
<style>
.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.kqezffzhk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25h17.5v7.5H3.25zm0 10h17.5v7.5H3.25z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qepuaqbvx {
  stroke: currentColor;
}

.qwn4--teq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 7h.01m-.01 10h.01");
}

.upeuobe7x {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.25 15.25l4.5 4.5m0-4.5l-4.5 4.5");
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

.va-cqqbhp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 7h5.5m-5.5 10h5.5");
}

</style>
