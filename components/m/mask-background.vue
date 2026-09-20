<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vyq_b1bgv"/><path clip-rule="evenodd" class="oese_3jol"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mask-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oese_3jol {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 8.8v4.267H6.093c.607 2.786 3.027 4.8 5.907 4.8c2.381 0 4.515-1.666 5.5-3.734H20v4.214C20 19.26 19.284 20 18.4 20H5.6c-.884 0-1.6-.74-1.6-1.653V8.8zm-4 5.333c-.848 1.282-2.384 2.134-4 2.134s-3.151-.852-4-2.134zM8.5 9.867c-1.254 0-2.328.887-2.5 2.133h1.478c.15-.48.508-.88 1.022-.88s.85.4 1 .88H11c-.172-1.246-1.246-2.133-2.5-2.133m7 0c-1.254 0-2.327.887-2.5 2.133h1.5c.15-.48.486-.88 1-.88s.85.4 1 .88H18c-.173-1.246-1.246-2.133-2.5-2.133M18.4 4c.884 0 1.6.74 1.6 1.653V7.2H4V5.653C4 4.74 4.716 4 5.6 4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vyq_b1bgv {
  fill: var(--svg-color--1c68f3, #1c68f3);
  d: path("M24 0H0v24h24z");
}

</style>
