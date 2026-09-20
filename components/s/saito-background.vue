<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mgt_oackn"/><path class="e9cwy4bau"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:saito-background" /></template>
<style>
.e9cwy4bau {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.023 7.931L12.098 4.02a.2.2 0 0 0-.054-.018h-.008a.2.2 0 0 0-.103.013h-.018l-6.92 3.908l-.014.008a.18.18 0 0 0-.093.152v7.828a.18.18 0 0 0 .089.15l6.934 3.912A.16.16 0 0 0 12 20a.16.16 0 0 0 .093-.027l6.935-3.911a.18.18 0 0 0 .084-.125v-7.85a.18.18 0 0 0-.089-.151zm-7.245 11.58L5.31 15.839l3.312-5.552l3.156 1.814zM5.332 8.376L8.31 10.11l-2.978 5.13zm6.89 3.725l3.396-1.943l3.05-1.76v7.397h-6.446V12.1m3.37-2.338l-2.659-4.396l-.426-.698l6.058 3.414zM11.933 4.42l3.339 5.52l-1.979 1.116L12 11.79L5.448 8.074zm.29 11.788h5.595l-5.596 3.303z");
}

.ft5dv1b6b {
  fill: none;
}

.mgt_oackn {
  fill: var(--svg-color--ea1d3a, #ea1d3a);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
