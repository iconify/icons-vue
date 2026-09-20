<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGVHzq3bUo)" class="r4i437pya"/><path class="zg48-xozn"/></g><defs><linearGradient id="SVGVHzq3bUo" x1="12" x2="12" y1="4.002" y2="20.002" gradientUnits="userSpaceOnUse"><stop class="a0ykbrpji"/><stop offset=".59" class="e5mvy2boz"/><stop offset="1" class="oce-nccuc"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:plastik-background" /></template>
<style>
.a0ykbrpji {
  stop-color: var(--svg-color--0440a8, #0440a8);
}

.e5mvy2boz {
  stop-color: var(--svg-color--00b4b0, #00b4b0);
}

.ft5dv1b6b {
  fill: none;
}

.oce-nccuc {
  stop-color: var(--svg-color--02bfa1, #02bfa1);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.zg48-xozn {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 12.003a8 8 0 1 1-2.425-5.74L16.5 7.316a6.5 6.5 0 1 0 1.85 3.33l-3.8 3.75l-.2.19v.01a3.5 3.5 0 1 1 .015-5.175l-1.075 1.055a2 2 0 1 0 .02 3.035l.175-.175l.085-.1l1.87-1.85v.02l2.365-2.325v-.005l1.11-1.1A7.97 7.97 0 0 1 20 12.002");
}

</style>
