<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zdpu9meqq"/><path class="hplk3ebvo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mps-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hplk3ebvo {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.445 4h-1.183a3.333 3.333 0 0 1-3.204 3.387h-.116A3.333 3.333 0 0 1 8.738 4H7.556c0 1.711.897 3.2 2.226 4c-1.333.8-2.226 2.289-2.226 4s.897 3.2 2.226 4c-1.333.8-2.226 2.289-2.226 4h1.182a3.333 3.333 0 0 1 3.209-3.387h.107A3.333 3.333 0 0 1 15.262 20h1.183c0-1.711-.898-3.2-2.227-4c1.333-.8 2.227-2.289 2.227-4s-.898-3.2-2.227-4c1.333-.8 2.227-2.289 2.227-4m-1.183 8a3.334 3.334 0 0 1-3.209 3.387h-.106A3.333 3.333 0 0 1 8.737 12a3.333 3.333 0 0 1 3.205-3.387h.116A3.333 3.333 0 0 1 15.262 12");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zdpu9meqq {
  fill: var(--svg-color--59c7f2, #59c7f2);
  d: path("M24 0H0v24h24z");
}

</style>
