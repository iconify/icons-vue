<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="r9v-uccxc"/><path class="e3w7r9bxa"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nos-background" /></template>
<style>
.e3w7r9bxa {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 19h1.5V7.38c0-.59.93-1.185 1.56-.46L12.5 17.5h-2L7.75 12H6l3.5 7h5.51L8.525 6.29s-.64-1.28-2.16-1.28S4 6.56 4 7.025zM20 5h-1.5v11.635c0 .585-.92 1.18-1.55.455L11.5 6.5h2l2.75 5.5H18l-3.49-7H9l6.485 12.72S16.125 19 17.65 19S20 17.45 20 16.985z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r9v-uccxc {
  fill: var(--svg-color--0de90b, #0de90b);
  d: path("M24 0H0v24h24z");
}

</style>
