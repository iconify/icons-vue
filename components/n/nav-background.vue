<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGxGA9Qclu)" class="r4i437pya"/><path clip-rule="evenodd" class="le31aobho"/></g><defs><linearGradient id="SVGxGA9Qclu" x1="20" x2="4.96" y1="4.533" y2="20.505" gradientUnits="userSpaceOnUse"><stop class="swqw-eaou"/><stop offset=".456" class="x2i2sniug"/><stop offset="1" class="szc7xzt4p"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nav-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.le31aobho {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.053 4.96a1.067 1.067 0 0 0-1.92.64v5.333H5.067a1.067 1.067 0 0 0 0 2.133h1.066V18.4a1.066 1.066 0 0 0 2.134 0v-5.333h3.2l4.48 5.973a1.065 1.065 0 0 0 1.92-.64v-5.333h1.066a1.067 1.067 0 0 0 0-2.134h-1.066V5.6a1.067 1.067 0 0 0-2.134 0v5.333h-3.2zm6.08 8.107l1.6 2.133v-2.133zm-4.266-2.134L8.267 8.8v2.133z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.swqw-eaou {
  stop-color: var(--svg-color--0b88f6, #0b88f6);
}

.szc7xzt4p {
  stop-color: var(--svg-color--dd1eba, #dd1eba);
}

.x2i2sniug {
  stop-color: var(--svg-color--7152d7, #7152d7);
}

</style>
