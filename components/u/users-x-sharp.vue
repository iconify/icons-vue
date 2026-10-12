<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><circle class="y-aluxb2e"/><path class="vqh6s1b7m"/></g><path class="upeuobe7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:users-x-sharp" /></template>
<style>
.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
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

.vqh6s1b7m {
  d: path("M3.5 20.25h11.75v-.75c0-2.9-2.7-5-6.25-5s-6.25 2.1-6.25 5v.75zM15 4.5a3.5 3.5 0 0 1 0 7m2.5 3.25l3.75 1.047v4.453H19");
}

.wil2krbkc {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-aluxb2e {
  cx: 9px;
  cy: 8px;
  r: 3.5px;
}

</style>
