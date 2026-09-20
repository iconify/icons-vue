<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGhkI44ckh)" class="r4i437pya"/><path class="t9usw4bwh"/></g><defs><linearGradient id="SVGhkI44ckh" x1="17.574" x2="5.454" y1="8.607" y2="16.364" gradientUnits="userSpaceOnUse"><stop class="yaob_zb7s"/><stop offset=".49" class="hkzli6b-b"/><stop offset="1" class="rv7l3y4gm"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:welt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hkzli6b-b {
  stop-color: var(--svg-color--b041ad, #b041ad);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rv7l3y4gm {
  stop-color: var(--svg-color--7f67cf, #7f67cf);
}

.t9usw4bwh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.388 4.438a.97.97 0 0 1-.286 1.348l-11.15 7.272a.971.971 0 0 1-1.057-1.63l11.15-7.271a.97.97 0 0 1 1.343.286zm-4.692 14.35a1.212 1.212 0 1 1-2.425 0a1.212 1.212 0 0 1 2.425 0m4.411-8.397a.972.972 0 0 0-1.066-1.624L5.89 16.04a.972.972 0 0 0 1.066 1.624z");
}

.yaob_zb7s {
  stop-color: var(--svg-color--cd5792, #cd5792);
}

</style>
