<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q-zb1_16q"/><path class="yi3xbob6z"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ton-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q-zb1_16q {
  fill: var(--svg-color--08c, #08c);
  d: path("M24 0H0v24h24z");
}

.yi3xbob6z {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.699 7.75l-6.974 11.107a.94.94 0 0 1-1.253.32a.94.94 0 0 1-.343-.325L4.292 7.746A1.97 1.97 0 0 1 4 6.711a2.04 2.04 0 0 1 2.066-2.005h11.878c1.134 0 2.056.894 2.056 2c0 .367-.104.73-.301 1.045M5.972 7.38l5.087 7.844V6.589H6.504c-.528 0-.763.348-.532.79m6.97 7.844l5.086-7.845c.236-.442-.005-.79-.531-.79H12.94z");
}

</style>
