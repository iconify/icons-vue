<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGuWdPOcSK)" class="r4i437pya"/><path class="r-wshnoqg"/></g><defs><linearGradient id="SVGuWdPOcSK" x1="12" x2="12" y1="5.867" y2="17.6" gradientUnits="userSpaceOnUse"><stop class="efnpo_7-d"/><stop offset=".28" class="m517v6bmw"/><stop offset=".58" class="a1-lmabet"/><stop offset=".78" class="q1zoetbhi"/><stop offset="1" class="h20629l3o"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:send-background" /></template>
<style>
.a1-lmabet {
  stop-color: var(--svg-color--846b52, #846b52);
}

.efnpo_7-d {
  stop-color: var(--svg-color--fdf6eb, #fdf6eb);
}

.ft5dv1b6b {
  fill: none;
}

.h20629l3o {
  stop-color: var(--svg-color--dfccaf, #dfccaf);
}

.m517v6bmw {
  stop-color: var(--svg-color--cfb89a, #cfb89a);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q1zoetbhi {
  stop-color: var(--svg-color--ad9173, #ad9173);
}

.r-wshnoqg {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.467 8.533H7.2V5.866h9.541c.907 0 2.726.534 2.726 2.667m-12.267 0v1.37c0 .23.133.763.667.763h9.466c.891 0 2.667.336 2.667 1.979v3.43c0 .458-.533 2.058-2.667 2.058H6.667c-.891 0-2.667-.448-2.667-2.64h12.667c.224 0 .666-.277.666-.827v-.533c0-.23-.133-.8-.666-.8h-10.8c-.667 0-1.334-.272-1.334-1.37v-3.43z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
