<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qixco3baf"/><path class="awstqro8t"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pokt-background" /></template>
<style>
.awstqro8t {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.008 11.441c0-3.313 2.97-4.091 4.99-3.921V4.077a7.983 7.983 0 0 0-3.493 15.507v-2.979a1.6 1.6 0 0 1 1.622-1.611h.913c2.19 0 2.455-2.06 2.455-2.435c0-.254-.105-.489-.225-.748a4 4 0 0 1-.17-.4a.8.8 0 0 1 .16-.783l.803-.624a4.42 4.42 0 0 1 .928 2.555c0 3.313-2.968 4.091-4.989 3.922v3.442A7.982 7.982 0 0 0 18.957 8.06a7.98 7.98 0 0 0-4.462-3.644v2.979a1.6 1.6 0 0 1-1.622 1.612h-.913c-2.19 0-2.455 2.06-2.455 2.434c0 .255.105.49.225.749c.06.125.12.254.17.399a.8.8 0 0 1-.16.783l-.803.624a4.43 4.43 0 0 1-.929-2.555");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qixco3baf {
  fill: var(--svg-color--1e8aed, #1e8aed);
  d: path("M24 0H0v24h24z");
}

</style>
