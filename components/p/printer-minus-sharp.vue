<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="qepuaqbvx"><path class="q_x-ecb9w"/><path class="e8nj4k-iu"/><path class="fmt7gtbnv"/></g><path class="fzh0ky66v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:printer-minus-sharp" /></template>
<style>
.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.e8nj4k-iu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 13.25h10.5v8H6.75z");
}

.fmt7gtbnv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 11h.01");
}

.fzh0ky66v {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 17.5h5.5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q_x-ecb9w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 17.25h-4v-9.5h18.5v9.5h-4m-10.5-9.5v-5h10.5v5");
}

.qepuaqbvx {
  stroke: currentColor;
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

</style>
