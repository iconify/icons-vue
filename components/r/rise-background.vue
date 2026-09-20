<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGeS2wZxQx)" class="r4i437pya"/><path class="j_rfx4b3h"/></g><defs><linearGradient id="SVGeS2wZxQx" x1="4.002" x2="20.002" y1="10.623" y2="12.097" gradientUnits="userSpaceOnUse"><stop class="cmwuixjqx"/><stop offset="1" class="ion3qacuq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rise-background" /></template>
<style>
.cmwuixjqx {
  stop-color: var(--svg-color--cc1a3c, #cc1a3c);
}

.ft5dv1b6b {
  fill: none;
}

.ion3qacuq {
  stop-color: var(--svg-color--ff9a2e, #ff9a2e);
}

.j_rfx4b3h {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.19 19.995a8.13 8.13 0 0 0 5.808-7.843C19.998 7.655 16.418 4 12 4s-7.998 3.649-7.998 8.153c0 3.728 2.455 6.872 5.809 7.847L11.5 9.998l-4.25 3.174l-.25-.255L12 6l4.999 6.918l-.25.25l-4.25-3.169z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
