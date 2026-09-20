<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGAzgWLe8G)" class="r4i437pya"/><path clip-rule="evenodd" class="n6v13fb_a"/></g><defs><linearGradient id="SVGAzgWLe8G" x1="4" x2="89.333" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="h35nacbyr"/><stop offset="1" class="gb-x_zb_s"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mantra-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gb-x_zb_s {
  stop-color: var(--svg-color--fe95ce, #fe95ce);
}

.h35nacbyr {
  stop-color: var(--svg-color--ffb298, #ffb298);
}

.n6v13fb_a {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12 4l1.778 1.707L12 7.395l-1.778-1.688zm-1.476 6.489a2.15 2.15 0 0 0 2.952 0l4.746-4.711L20 7.11V20h-1.778V8.818l-2.969 2.79c-.889.854-2.08 1.28-3.253 1.28s-2.364-.426-3.253-1.28L5.777 8.8V20H4V7.11l1.778-1.332z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
