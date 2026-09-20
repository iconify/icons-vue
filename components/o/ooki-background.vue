<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hnmu31bvo"/><path clip-rule="evenodd" class="ph3swyxxr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ooki-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hnmu31bvo {
  fill: var(--svg-color--f6be4e, #f6be4e);
  d: path("M24 0H0v24h24z");
}

.ph3swyxxr {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.092 19.199a7.7 7.7 0 0 1-3.019.532a7.73 7.73 0 0 1-7.451-4.693A7.74 7.74 0 0 1 12.073 4.27a7.733 7.733 0 0 1 3.018 14.93m-5.58-7.328a.484.484 0 1 1-.685-.684a.484.484 0 0 1 .685.684m5.807 0a.484.484 0 1 1-.685-.685a.484.484 0 0 1 .685.685m-3.982.407c.01-.15.107-.256.252-.266h.973c.101 0 .222.097.242.208a.6.6 0 0 1-.044.315a.65.65 0 0 1-.174.266a.7.7 0 0 1-.503.18a.85.85 0 0 1-.533-.185a.66.66 0 0 1-.213-.518");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
