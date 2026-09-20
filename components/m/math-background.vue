<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="uq5m0bb2r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:math-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uq5m0bb2r {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M9 10.2a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0 3.2a1 1 0 1 0 0-2a1 1 0 0 0 0 2m7-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-8.6-.6a1 1 0 1 0 0-2a1 1 0 0 0 0 2m7-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-3.8 1a1 1 0 1 0 0-2a1 1 0 0 0 0 2m7-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-2.6-.6a1 1 0 1 0 0-2a1 1 0 0 0 0 2m-2.2 2.4a.8.8 0 1 1-1.6 0a.8.8 0 0 1 1.6 0M10.4 15a.8.8 0 1 0 0-1.598a.8.8 0 0 0 0 1.598m8.4-2.4a.8.8 0 1 1-1.6 0a.8.8 0 0 1 1.6 0m-2 2.4a.8.8 0 1 0 0-1.6a.8.8 0 0 0 0 1.6m-10-2.4a.8.8 0 1 1-1.6 0a.8.8 0 0 1 1.6 0m-2.4 1.6a.4.4 0 1 0 0-.8a.4.4 0 0 0 0 .8m2 1.2a.4.4 0 1 1-.8 0a.4.4 0 0 1 .8 0m5.6.4a.4.4 0 1 0 0-.8a.4.4 0 0 0 0 .801m6.4-.4a.4.4 0 1 1-.801 0a.4.4 0 0 1 .801 0m1.2-1.2a.4.4 0 1 0 0-.8a.4.4 0 0 0 0 .8m-11.4 0a.8.8 0 1 1-1.6 0a.8.8 0 0 1 1.6 0m5.2.8a.8.8 0 1 0 0-1.598a.8.8 0 0 0 0 1.598");
}

</style>
