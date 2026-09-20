<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="k06x_4bey"/><path class="p3rrsoapn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nrg-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k06x_4bey {
  fill: var(--svg-color--0bc98d, #0bc98d);
  d: path("M24 0H0v24h24z");
}

.p3rrsoapn {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.8 8.785l-4.8 4.92L10.26 12l3.02-3.09L12 7.56l-4.7 4.585L12 16.71l6.4-6.31L20 12l-8 8l-8-8l8-8z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
