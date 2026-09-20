<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f3tcthbqu"/><path class="wsevbnbjr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tusd-background" /></template>
<style>
.f3tcthbqu {
  fill: var(--svg-color--1b5aff, #1b5aff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wsevbnbjr {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.333 4H4v5.333A5.333 5.333 0 0 0 9.333 4m0 16V9.328C9.333 6.384 11.536 4 14.528 4H20v5.333h-5.333V20z");
}

</style>
