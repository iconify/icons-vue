<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qkmr-kbck"/><path class="bov2gvl_n"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xrune-background" /></template>
<style>
.bov2gvl_n {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.235 12.941L15.308 4l-2.842 7.059h3.299L8.758 20l2.819-7.059z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qkmr-kbck {
  fill: var(--svg-color--28dbd1, #28dbd1);
  d: path("M24 0H0v24h24z");
}

</style>
