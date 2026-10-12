<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><path class="fha6990wp"/><path class="ydyxs3b_d"/></g><path class="go6cdpb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-star-sharp" /></template>
<style>
.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.fha6990wp {
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

.go6cdpb0v {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.54 13.92l.83 1.82l.15.32l.34.04l2 .22l.34.04l-.25.24l-1.48 1.35l-.26.24l.07.34l.4 1.96l.07.35l-.3-.18l-1.75-.99l-.3-.17l-.3.17l-1.75.99l-.3.18l.07-.35l.4-1.96l.07-.34l-.26-.24l-1.48-1.35l-.25-.24l.34-.04l2-.22l.34-.04l.15-.32l.83-1.82l.14-.32z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

.wil2krbkc {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydyxs3b_d {
  d: path("m6.5 8.75l4.1 3.1l1.4.988l1.4-.988l4.1-3.1");
}

</style>
