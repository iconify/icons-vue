<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gr8o02b7c"/><path class="uaymm8bfn"/><path class="ufb1gdceo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:neo-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gr8o02b7c {
  fill: var(--svg-color--00e599, #00e599);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uaymm8bfn {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.294 20l-6.118-2.541V6.87L13.332 4l5.402 2.513l-7.44 2.663z");
}

.ufb1gdceo {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.823 17.176l-7.058-2.899V9.571l7.058-2.626z");
}

</style>
