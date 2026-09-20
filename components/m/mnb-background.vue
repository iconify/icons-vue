<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG9Bg8CbYu)" class="r4i437pya"/><path class="mzy0p8bgo"/></g><defs><linearGradient id="SVG9Bg8CbYu" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="xdjc2bc9l"/><stop offset="1" class="obga35bot"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mnb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mzy0p8bgo {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 4l1.882 1.12v1.506l4.236 2.503v3.455l-.941.611V9.647l-5.135-3.082l-.268-.198l.857-.485l.508.302v-.631L12 4.885l-1.139.673v1.355l1.14.673l.427-.254l.744.442l-.701.419v.96l2.823 1.675v3.388l.87.513l1.45-.847l1.915 1.12v2.231l-1.915 1.12l-1.426-.833L12 20l-2.823-1.67v-1.06L12 18.966l5.073-3.045l.452-.24v1.045l-.588.348l.677.39l1.158-.672v-1.356l-1.158-.673l-1.162.673v.5l-.753.441v-1.035l-.715-.414L12 16.706l-2.965-1.76l-.8.47v1.822l-1.882 1.115l-1.882-1.12v-2.23l1.411-.843V9.13L8.8 7.401l.894.518l-2.87 1.727v6.612l-.942-.574v-.64l-.668.395v1.355l1.139.673l1.139-.673v-1.36l-.358-.212v-.87l.697.41l.875-.514v-3.426l2.823-1.675v-.96l-1.411-.842V5.11zm1.624 7.515L12 10.545l-1.614.966l1.642.927l1.6-.923zm-3.511 2.396l1.647.978v-1.948l-1.647-.974zm2.15.96l1.62-.96V12l-1.615.941v1.925z");
}

.obga35bot {
  stop-color: var(--svg-color--082e9a, #082e9a);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xdjc2bc9l {
  stop-color: var(--svg-color--2de7f4, #2de7f4);
}

</style>
