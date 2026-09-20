<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGbsn9ebsW)" class="r4i437pya"/><path class="x247-sbfi"/></g><defs><linearGradient id="SVGbsn9ebsW" x1="16.143" x2="7.643" y1="5.786" y2="18.751" gradientUnits="userSpaceOnUse"><stop class="os6c1bb_i"/><stop offset="1" class="ezqfkqbwd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xy-background" /></template>
<style>
.ezqfkqbwd {
  stop-color: var(--svg-color--1033b3, #1033b3);
}

.ft5dv1b6b {
  fill: none;
}

.os6c1bb_i {
  stop-color: var(--svg-color--13c0e4, #13c0e4);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.x247-sbfi {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 17.25l5.5-6l-4-4.5H11l1.5 1.5l3.5-3.5h4L6.5 19.25zm8.75-3l1.25 1.5h5.75l-4-4.5z");
}

</style>
