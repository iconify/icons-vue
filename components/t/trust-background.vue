<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="igi_-gs6l"/><path class="cglk3sn_s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trust-background" /></template>
<style>
.cglk3sn_s {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.8 6.311L12 4v16c-5.143-2.134-7.2-6.222-7.2-8.533zm14.4 0L12 4v16c5.143-2.134 7.2-6.222 7.2-8.533z");
}

.ft5dv1b6b {
  fill: none;
}

.igi_-gs6l {
  fill: var(--svg-color--0500ff, #0500ff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
