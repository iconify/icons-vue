<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGopqyqczb)" class="r4i437pya"/><path class="p16ymd34w"/></g><defs><linearGradient id="SVGopqyqczb" x1="7.894" x2="13.503" y1="5.92" y2="18.391" gradientUnits="userSpaceOnUse"><stop class="zvx4p2bdg"/><stop offset="1" class="l1yx5aczi"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mxm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l1yx5aczi {
  stop-color: var(--svg-color--4af2cf, #4af2cf);
}

.p16ymd34w {
  fill: var(--svg-color--000, #000);
  d: path("M13.427 5h-2.919L4 16.405L5.47 19h12.995L20 16.405zM5.375 16l5.672-10h1.25l-4.99 9h5.735l.665 1zm3.655-2l4.152-7.479l5.658 9.817l-.63 1.163l-5.029-8.669L10.353 14zm2.47 0l.5-1l.5 1zm1.697-3.198l4.167 7.195H6.03L5.417 17h10.116l-2.919-5.136z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.zvx4p2bdg {
  stop-color: var(--svg-color--18dbeb, #18dbeb);
}

</style>
