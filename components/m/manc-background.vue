<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="l7fm0-bmj"/><path class="h8w7i1e5k"/><path class="grmqznyac"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:manc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.grmqznyac {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.461 7.367c-2.51 0-4.724 2.05-4.724 4.577v3.423a1.263 1.263 0 1 0 2.526 0v-3.305c0-1.432.775-2.59 2.198-2.59c1.42 0 2.434 1.163 2.434 2.59v3.516a1.053 1.053 0 0 0 2.105 0v-3.634c0-2.526-2.034-4.577-4.539-4.577");
}

.h8w7i1e5k {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.539 7.367A4.56 4.56 0 0 0 4 11.944v3.634a1.053 1.053 0 1 0 2.105 0v-3.516c0-1.432 1.015-2.59 2.434-2.59c1.423 0 2.198 1.163 2.198 2.59v3.398a1.173 1.173 0 0 0 2.345 0v-3.516c0-2.526-2.033-4.577-4.543-4.577");
}

.l7fm0-bmj {
  fill: var(--svg-color--252060, #252060);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
