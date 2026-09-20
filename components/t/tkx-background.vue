<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="utrm8wxmk"/><path clip-rule="evenodd" class="ysclfvbnl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tkx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utrm8wxmk {
  fill: var(--svg-color--f26829, #f26829);
  d: path("M24 0H0v24h24z");
}

.ysclfvbnl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6.81 15.166a5.1 5.1 0 0 1-.8-2.17s1.696-.015 1.99 0v-2H4.08c-.03 0-.045 0-.05.03c-.03.41-.035.79-.025 1.14a8.06 8.06 0 0 0 6.802 7.737a7.99 7.99 0 0 0 8.747-5.307q.415-1.179.446-2.605a5 5 0 0 0-.035-.646a8.055 8.055 0 0 0-9.193-7.252C8.02 4.518 5.62 6.41 4.605 9H6.67a6.28 6.28 0 0 1 6.437-2.986a5.7 5.7 0 0 1 2.451 1.02a.03.03 0 0 1 .01.015v.01l-.005.01l-3.56 3.541l-.012.008l-.014.002a.04.04 0 0 1-.025-.01l-1.5-1.505l-.003-.004l-.004-.003h-.004l-.004.002l-1.356 1.35l-.008.011l-.002.014c0 .005 0 .015.01.02l1.496 1.486l.01.03c0 .01 0 .02-.01.025l-1.5 1.5q-.015.009 0 .025l1.315 1.325l.011.008l.014.002a.03.03 0 0 0 .03-.01l1.5-1.5l.013-.003q.006 0 .012.003h.005l3.476 3.466q.008.007.013.017a.05.05 0 0 1 0 .041l-.013.017a6.4 6.4 0 0 1-3.751 1.15a5.9 5.9 0 0 1-3.15-1.02q-.515-.336-.921-.795a10 10 0 0 1-.82-1.096m10.134.37a5.93 5.93 0 0 0 1.125-4.19a5.77 5.77 0 0 0-1.13-2.897a.04.04 0 0 0-.03 0l-.015.005l-3.506 3.512a.04.04 0 0 0-.011.027q0 .016.01.027l3.517 3.522a.03.03 0 0 0 .03 0h.01z");
}

</style>
