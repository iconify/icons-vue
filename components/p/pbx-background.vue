<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGam0yJebJ)" class="r4i437pya"/><path class="u_2-bl77e"/><path class="i989orb6a"/><path class="dvelmolsc"/></g><defs><linearGradient id="SVGam0yJebJ" x1="11.324" x2="16.101" y1="12.602" y2="8.61" gradientUnits="userSpaceOnUse"><stop class="cwmfu3bnu"/><stop offset="1" class="mphrhkbdr"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pbx-background" /></template>
<style>
.cwmfu3bnu {
  stop-color: var(--svg-color--0080ee, #0080ee);
}

.dvelmolsc {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.519 10.002v7.434c0 1.899 1.935 3.137 3.58 2.296l.542-.279c2.683-1.393 2.405-5.443-.438-6.428c-2.038-.692-3.684-1.156-3.684-3.024M9.71 4.004c.67.738 2.094 1.672 5.169 2.27c1.556.305 3.037.911 4.36 1.786a5.75 5.75 0 0 0-5.51-4.056z");
}

.ft5dv1b6b {
  fill: none;
}

.i989orb6a {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.121 8.55C6.304 7.157 6.077 5.764 6.325 4.887a4.42 4.42 0 0 0-1.806 3.56V15.5h9.21c1.356 0 2.6-.599 3.575-1.367c-.48-3.364-4.334-3.684-8.183-5.583");
}

.mphrhkbdr {
  stop-color: var(--svg-color--01c5f6, #01c5f6);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.u_2-bl77e {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.728 15.371H4.52V8.442C4.519 5.986 6.531 4 9.018 4h4.71c3.173.005 5.753 2.549 5.753 5.685c0 3.137-2.58 5.686-5.753 5.686");
}

</style>
