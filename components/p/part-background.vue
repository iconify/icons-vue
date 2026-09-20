<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGAxpwOd4s)" class="r4i437pya"/><path class="k73vvhbmi"/></g><defs><linearGradient id="SVGAxpwOd4s" x1="12" x2="12" y1="4.01" y2="19.99" gradientUnits="userSpaceOnUse"><stop class="werbo0z-f"/><stop offset="1" class="otj1g29tg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:part-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k73vvhbmi {
  fill: var(--svg-color--fff, #fff);
  d: path("M8 6.01a2 2 0 0 0-2 2v9.17a4.5 4.5 0 0 0 .691 2.397l.26.413A2.95 2.95 0 0 1 4 17.039v-9.03a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v7.98a4 4 0 0 1-4 4H9.993a2 2 0 0 1-2-2v-8.5a1.5 1.5 0 0 1 1.5-1.5h5a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 1-1.5 1.5h-4.5v2H16a2 2 0 0 0 2-2V8.01a2 2 0 0 0-2-2zm1.993 7.98h4v-4h-4z");
}

.otj1g29tg {
  stop-color: var(--svg-color--45d693, #45d693);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.werbo0z-f {
  stop-color: var(--svg-color--26f294, #26f294);
}

</style>
