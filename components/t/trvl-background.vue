<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGAO0lE8IY)" class="r4i437pya"/><path class="dp0_4e_6m"/></g><defs><linearGradient id="SVGAO0lE8IY" x1="18.4" x2="4.01" y1="4.42" y2="18.41" gradientUnits="userSpaceOnUse"><stop class="u306osbex"/><stop offset="1" class="l-jphgqml"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trvl-background" /></template>
<style>
.dp0_4e_6m {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 12c0 .5-.25 2.51-3.005 2.51c-1.955 0-3.48-1.2-4.325-1.885a.04.04 0 0 0-.05 0a.04.04 0 0 0-.01.055c.69.85 1.89 2.355 1.89 4.32c0 1.425-1.9 3-2.5 3v-8zM7 9.5c1.955 0 3.475 1.195 4.325 1.885a.04.04 0 0 0 .03.014l.016-.004l.014-.01a.04.04 0 0 0 0-.055c-.69-.85-1.89-2.37-1.89-4.33c0-3 2.255-3 2.505-3v8H4c0-.25 0-2.5 3-2.5");
}

.ft5dv1b6b {
  fill: none;
}

.l-jphgqml {
  stop-color: var(--svg-color--c1d0d1, #c1d0d1);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.u306osbex {
  stop-color: var(--svg-color--8fa3a4, #8fa3a4);
}

</style>
