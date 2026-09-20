<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG9nD6zbLn)" class="r4i437pya"/><path clip-rule="evenodd" class="tajdp0b2k"/></g><defs><linearGradient id="SVG9nD6zbLn" x1="12" x2="12" y1="4.498" y2="19.497" gradientUnits="userSpaceOnUse"><stop class="txrgv-pxc"/><stop offset="1" class="u0lfcebpw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:srlty-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tajdp0b2k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6.55 4.497c-1.365 3.335-.66 6.635-.135 7.87L4 14.497h1.79l3.865-3.25c.2.5.595 1.62.595 2.13c0 .28-.21.85-.45 1.48c-.29.795-.62 1.69-.62 2.25c0 .8.46 1.93.685 2.395h4.21c.225-.455.67-1.575.67-2.4c0-.52-.25-1.23-.5-1.93c-.24-.675-.475-1.33-.475-1.8c0-.75.395-1.73.59-2.12l3.83 3.245H20l-2.42-2.125c1.205-3.26.425-6.6-.115-7.87l-3.915 4.76c-.135-.125-.63-.26-1.56-.26s-1.55.135-1.74.26zm.515 2.535l2.21 2.86l-1.96 1.585c-.25-.7-.645-2.56-.25-4.445m9.775 0l-2.21 2.86l1.965 1.585c.25-.7.645-2.56.25-4.445zm-6.23 3.34c.23.795.685 2.535.685 3.155c0 .37-.22.995-.45 1.65c-.26.715-.525 1.47-.525 1.96c0 .75.24 1.26.36 1.36h.82v-1.5h1v1.5h.63c.15-.16.45-.75.45-1.36c0-.4-.28-1.2-.55-1.96c-.24-.69-.475-1.35-.475-1.65c0-.5.49-2.31.735-3.155c-.2-.115-.755-.35-1.37-.35c-.61 0-1.13.235-1.31.35M5.5 19.497v-3.565l1-.91v3.475h2.12s.25.635.38 1zm13-3.585v3.585H15c.125-.37.38-1 .38-1h2.12v-3.5z");
}

.txrgv-pxc {
  stop-color: var(--svg-color--2691ff, #2691ff);
}

.u0lfcebpw {
  stop-color: var(--svg-color--02d15b, #02d15b);
}

</style>
