<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVG3LzDRd7h)" class="i7hzf0xyh"/><path fill="url(#SVGBdDxo07i)" class="erf8684lb"/><path fill="url(#SVGghybzecr)" class="mnc2kusdg"/><path fill="url(#SVGwaqUGece)" class="qb6tzwb2v"/></g><defs><linearGradient id="SVG3LzDRd7h" x1="11.997" x2="11.997" y1="4" y2="20.005" gradientUnits="userSpaceOnUse"><stop class="b_fvvlz7a"/><stop offset="1" class="rano1jbzh"/></linearGradient><linearGradient id="SVGBdDxo07i" x1="11.997" x2="11.997" y1="4.001" y2="19.945" gradientUnits="userSpaceOnUse"><stop class="dtcgcg9vz"/><stop offset=".7" class="w7rj_bcgn"/></linearGradient><linearGradient id="SVGghybzecr" x1="13.187" x2="10.984" y1="12.842" y2="20.648" gradientUnits="userSpaceOnUse"><stop class="s48hmmbov"/><stop offset=".56" class="n3efd8cmk"/></linearGradient><linearGradient id="SVGwaqUGece" x1="8.904" x2="9.616" y1="8.192" y2="11.628" gradientUnits="userSpaceOnUse"><stop class="mz7dz8bnk"/><stop offset=".61" class="ya1zc1ykq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stsol-background" /></template>
<style>
.b_fvvlz7a {
  stop-color: var(--svg-color--498be9, #498be9);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.dtcgcg9vz {
  stop-color: var(--svg-color--4a8cea, #4a8cea);
}

.erf8684lb {
  d: path("m16.554 11.203l-4.557 2.676l-4.56-2.68l4.574-2.392z");
}

.ft5dv1b6b {
  fill: none;
}

.i7hzf0xyh {
  d: path("m11.997 13.868l-4.556-2.676l-.129.196a5.636 5.636 0 0 0 .756 6.975a5.535 5.535 0 0 0 7.86 0a5.62 5.62 0 0 0 .755-6.975l-.13-.196z");
}

.mnc2kusdg {
  d: path("m11.997 4l3.934 6.134l-3.934 2.312z");
}

.mz7dz8bnk {
  stop-color: var(--svg-color--ffe235, #ffe235);
}

.n3efd8cmk {
  stop-color: var(--svg-color--568fdd, #568fdd);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qb6tzwb2v {
  d: path("M11.998 4v8.446l-3.925-2.312z");
}

.rano1jbzh {
  stop-color: var(--svg-color--56f2ff, #56f2ff);
}

.s48hmmbov {
  stop-color: var(--svg-color--fb8174, #fb8174);
}

.w7rj_bcgn {
  stop-color: var(--svg-color--5abef4, #5abef4);
}

.ya1zc1ykq {
  stop-color: var(--svg-color--5dcba2, #5dcba2);
}

</style>
