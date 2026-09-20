<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="g5t9hzqjn"/><path clip-rule="evenodd" class="g3-80cbhz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wnxm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g3-80cbhz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.476 8.719a2.6 2.6 0 0 0 .318-3.956a2.606 2.606 0 0 0-3.687 0a2.607 2.607 0 0 0 .427 4.031l.005.012a1.262 1.262 0 1 1-1.68 1.869l-.015-.008l-.019-.03a1.3 1.3 0 0 1-.147-.213a2.606 2.606 0 0 0-3.914-.26a2.607 2.607 0 1 0 4.022 3.276l.024-.009a1.263 1.263 0 1 1 1.435 1.988v.004a2.6 2.6 0 0 0-.704 2.969a2.606 2.606 0 0 0 4.252.845a2.607 2.607 0 0 0-.442-4.04l.012-.003l-.002-.007a1.295 1.295 0 1 1 1.808-1.798l.013.004a2.608 2.608 0 1 0 4.053-3.228a2.607 2.607 0 0 0-3.911.255a1.295 1.295 0 1 1-1.851-1.696zm-.025-2.114a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 1 1 1.06-2.56a1.5 1.5 0 0 1 .44 1.06m3.94 6.902a1.501 1.501 0 0 0 1.062-2.56a1.5 1.5 0 1 0-1.061 2.56m-9.282-1.5a1.5 1.5 0 1 1-3.001 0a1.5 1.5 0 0 1 3.001 0m3.841 6.887a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m1.107-12.289a1.107 1.107 0 1 1-2.214 0a1.107 1.107 0 0 1 2.214 0M11.95 18.5a1.108 1.108 0 1 0-.001-2.215a1.108 1.108 0 0 0 .001 2.215m6.549-6.493a1.108 1.108 0 1 1-2.215-.001a1.108 1.108 0 0 1 2.215.001M6.607 13.114a1.11 1.11 0 0 0 1.108-1.107a1.107 1.107 0 1 0-1.108 1.107");
}

.g5t9hzqjn {
  fill: var(--svg-color--1eab89, #1eab89);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
