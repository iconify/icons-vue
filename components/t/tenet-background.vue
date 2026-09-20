<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="oa8-zib0f"/><path class="m15dr7bwj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tenet-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m15dr7bwj {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.224 17.969a2.57 2.57 0 0 1-4.45 0L4.337 8.553a2.54 2.54 0 0 1 2.225-3.806h10.871c1.965 0 3.2 2.11 2.225 3.8l-5.435 9.427zm-1.25-11.102a1.074 1.074 0 0 0-1.95 0l-2.41 4.646c-.151.3-.151.67-.001.97l2.41 4.64a1.074 1.074 0 0 0 1.95 0l2.41-4.64c.15-.3.15-.67 0-.97l-2.41-4.64z");
}

.oa8-zib0f {
  fill: var(--svg-color--261c37, #261c37);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
