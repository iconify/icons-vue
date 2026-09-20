<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGp1oS2cuL)" class="r4i437pya"/><path class="c11rl-4eb"/></g><defs><linearGradient id="SVGp1oS2cuL" x1="6.769" x2="13.654" y1="8.119" y2="18.427" gradientUnits="userSpaceOnUse"><stop class="wfx8d3rcp"/><stop offset=".34" class="aokh7fb6q"/><stop offset=".62" class="xsqhskbyl"/><stop offset=".93" class="vn8if_mqj"/><stop offset="1" class="f40fylb4v"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:neer-background" /></template>
<style>
.aokh7fb6q {
  stop-color: var(--svg-color--335df7, #335df7);
}

.c11rl-4eb {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 6.63v6.74c0 .07.055.13.125.13h2.75c.075 0 .125-.06.125-.13v-3.245c0-.07.06-.125.13-.125h2.245c.07 0 .125-.06.125-.135V6.63a.125.125 0 0 0-.125-.13h-5.25A.125.125 0 0 0 4 6.63m0 7.99c0-.065.05-.12.12-.12h2.76c.065 0 .12.05.12.12v2.76c0 .065-.05.12-.12.12H4.12a.12.12 0 0 1-.12-.12zm6.5 2.76V6.63c0-.065.055-.125.125-.125h7.23c.03 0 .065.015.09.04l2.02 2.01c.02.025.035.06.035.09v8.735c0 .07-.055.12-.125.12h-2.76c-.07 0-.115-.05-.115-.12v-7.255c0-.07-.065-.125-.135-.125H13.65c-.07 0-.15.05-.15.125v7.255c0 .07-.035.12-.1.12h-2.775c-.07 0-.125-.05-.125-.12");
}

.f40fylb4v {
  stop-color: var(--svg-color--4e2ead, #4e2ead);
}

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

.vn8if_mqj {
  stop-color: var(--svg-color--702eb6, #702eb6);
}

.wfx8d3rcp {
  stop-color: var(--svg-color--0bd4f9, #0bd4f9);
}

.xsqhskbyl {
  stop-color: var(--svg-color--5551cb, #5551cb);
}

</style>
