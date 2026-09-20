<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="of6xb1vwi"/><path class="yjlt9ac3b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stpt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.of6xb1vwi {
  fill: var(--svg-color--24aae1, #24aae1);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yjlt9ac3b {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.5 4H12l-6.5 8H12zm0 8H12l-6.5 8H12z");
}

</style>
