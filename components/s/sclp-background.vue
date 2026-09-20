<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG8AW9IbSK)" class="r4i437pya"/><path class="pcf862hxf"/><path class="fap450bha"/></g><defs><linearGradient id="SVG8AW9IbSK" x1="17.127" x2="-2.31" y1="-1.871" y2="53.375" gradientUnits="userSpaceOnUse"><stop class="tkk09cb1k"/><stop offset=".38" class="c7nqqjb5v"/><stop offset="1" class="q4qrdtwyi"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sclp-background" /></template>
<style>
.c7nqqjb5v {
  stop-color: var(--svg-color--3a8afa, #3a8afa);
}

.fap450bha {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.533 17.5c-2.691 2.687-5.858 3.172-8.719 1.624l1.14-1.186l2.606-2.696l2.592-2.592a.693.693 0 0 0 0-.97l-2.602-2.6l3.195-3.341l.282-.292c.47.33.941.73 1.388 1.177c3.355 3.345 3.496 7.495.118 10.878");
}

.ft5dv1b6b {
  fill: none;
}

.pcf862hxf {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.265 4.957l-3.811 3.92a.2.2 0 0 0-.038.032L8.65 11.676a.684.684 0 0 0 0 .97l2.62 2.62l-3.227 3.388a10 10 0 0 1-1.45-1.22c-3.382-3.373-3.5-7.55-.093-10.962c2.7-2.7 5.886-3.157 8.765-1.515");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q4qrdtwyi {
  stop-color: var(--svg-color--1a6af4, #1a6af4);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tkk09cb1k {
  stop-color: var(--svg-color--00deca, #00deca);
}

</style>
