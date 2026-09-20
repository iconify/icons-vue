<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGdQXuVbQq)" class="r4i437pya"/><path class="riwzjtq3p"/></g><defs><linearGradient id="SVGdQXuVbQq" x1="6.105" x2="21.387" y1="4" y2="15.26" gradientUnits="userSpaceOnUse"><stop class="zqc_bfb8q"/><stop offset="1" class="d6ntvh61n"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pac-background" /></template>
<style>
.d6ntvh61n {
  stop-color: var(--svg-color--0290a4, #0290a4);
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

.riwzjtq3p {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.895 12L12 4l-5.895 8l5.053 6.821v-6.855l-.762 3.226l-2.421-3.188l4.03-5.419L16.03 12l-2.426 3.187L12 8.78V20z");
}

.zqc_bfb8q {
  stop-color: var(--svg-color--00ddf8, #00ddf8);
}

</style>
