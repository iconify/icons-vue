<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="yphc5nruy"/><path clip-rule="evenodd" class="dfgfrhbtc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:npc-background" /></template>
<style>
.dfgfrhbtc {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-7.134-3.618a.31.31 0 0 0-.34.386l1.345 5.197H9.724a.31.31 0 0 0 0 .62h4.55a.31.31 0 0 0 .3-.387l-1.447-5.585a.31.31 0 0 0-.26-.231m-3.654 8.272c-.176 0-.315.114-.315.259H8.89c0 .145.14.258.316.258h5.585c.176 0 .315-.113.315-.258s-.14-.259-.315-.259zm-.574-7.757a.776.776 0 1 0 0-1.551a.776.776 0 0 0 0 1.551m7.499-.775a.776.776 0 1 1-1.552 0a.776.776 0 0 1 1.552 0");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yphc5nruy {
  fill: var(--svg-color--bcbcbc, #bcbcbc);
  d: path("M24 0H0v24h24z");
}

</style>
