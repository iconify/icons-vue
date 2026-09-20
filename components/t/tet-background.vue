<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zzeta9bdk"/><path clip-rule="evenodd" class="jzef-mbpv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tet-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jzef-mbpv {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.285 4.27a1.2 1.2 0 0 0-.421.69v-.005L5.09 18.576A1.194 1.194 0 0 0 6.275 20h8.672a1.205 1.205 0 0 0 1.178-.96L18.91 5.424A1.202 1.202 0 0 0 17.72 4H9.048c-.278 0-.547.094-.763.27m3.13 4.53l-1.659 7.792h-.01a1.3 1.3 0 0 0-.043.283c0 .112.186.459 1.04.459c.848 0 1.242-.16 1.35-.694c.085-.426 1.124-5.472 1.636-7.84h2.272c.262-.037.79-.144.79-1.05c0-.432-.25-.55-.41-.55H9.5c-.236.043-.71.16-.71 1.067c0 .277.17.533.437.533z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zzeta9bdk {
  fill: var(--svg-color--487bff, #487bff);
  d: path("M24 0H0v24h24z");
}

</style>
