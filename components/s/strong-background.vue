<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="engqe-t1m"/><path clip-rule="evenodd" class="ld7crub8t"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:strong-background" /></template>
<style>
.engqe-t1m {
  fill: var(--svg-color--1668b0, #1668b0);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.ld7crub8t {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-.941 0A7.059 7.059 0 1 1 4.94 12a7.059 7.059 0 0 1 14.118 0m-5.31-4.706l2.957 2.212v.141H9.647V12h4.235v1.884H7.294v-6.59zm-3.631 2.824h6.588v6.588h-6.491l-2.92-2.185v-.166h7.058v-2.826h-4.235z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
