<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uq2h0y4eh"/><path class="zi5ui6btw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:waves-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uq2h0y4eh {
  fill: var(--svg-color--1857f5, #1857f5);
  d: path("M24 0H0v24h24z");
}

.zi5ui6btw {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 12l8-8l8 8l-8 8z");
}

</style>
