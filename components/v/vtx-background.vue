<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hh0a1rbhy"/><path class="zx-_mv50g"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vtx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hh0a1rbhy {
  fill: var(--svg-color--6869e6, #6869e6);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zx-_mv50g {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 5.176l8 13.647l8-13.647zm13.666 0L12 14.885L7.454 7.059h4.433L10.8 8.974l1.186 1.986l3.388-5.784z");
}

</style>
