<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w6ns7best"/><path class="f8lf87bdb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vite-background" /></template>
<style>
.f8lf87bdb {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 8.2L9 7l-.5 12.5zm6-1.355L20 4.5L8.65 19.355L10 6.85z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w6ns7best {
  fill: var(--svg-color--007aff, #007aff);
  d: path("M24 0H0v24h24z");
}

</style>
