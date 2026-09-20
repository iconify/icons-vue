<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="quc5b3wzk"/><path class="gfjbtov6z"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vib-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gfjbtov6z {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.571 4H5.428l9.143 16h4V4h-2.857v12.286z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.quc5b3wzk {
  fill: var(--svg-color--ff1e43, #ff1e43);
  d: path("M24 0H0v24h24z");
}

</style>
