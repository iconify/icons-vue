<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGAJqJOYLj)" class="r4i437pya"/><path class="i6zjb-b5y"/><path class="wmht5v14o"/></g><defs><linearGradient id="SVGAJqJOYLj" x1="6.526" x2="20.331" y1="16.863" y2="12.994" gradientUnits="userSpaceOnUse"><stop class="nbg31vb5l"/><stop offset="1" class="uun36chmi"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pwr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i6zjb-b5y {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.998 19.998a8.004 8.004 0 0 0 7.868-6.543a8 8 0 0 0-.176-3.664q.06.345.06.705c0 3.2-3.166 4.001-4.75 4.001H8.997l-.5 2.5h-2.75a8 8 0 0 0 6.25 3.001");
}

.nbg31vb5l {
  stop-color: var(--svg-color--4d4d4d, #4d4d4d);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uun36chmi {
  stop-color: var(--svg-color--1a1a1a, #1a1a1a);
}

.wmht5v14o {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.547 16.732a8 8 0 1 1 13.802-7.897c-.46-.775-1.385-1.34-3.1-1.34H8.997l-2.5 2.5h8.502v-1l3 2l-3 2.001v-1H6.496z");
}

</style>
