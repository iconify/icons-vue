<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ye7uxbcwu"/><path class="fozj2vbwm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mcade-background" /></template>
<style>
.fozj2vbwm {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.439 4.78a.78.78 0 1 1 1.56 0v.793a6.3 6.3 0 0 0-1.56.3zm0 12.957v1.483a.78.78 0 1 0 1.56 0v-1.183a6.2 6.2 0 0 1-1.56-.3m2.342.3v1.183a.78.78 0 1 0 1.56 0v-1.483a6.3 6.3 0 0 1-1.56.3m1.56-12.164V4.78a.78.78 0 1 0-1.56 0v.793a6.3 6.3 0 0 1 1.56.3m2.732 2.81L12.39 12l4.683 3.317c-1.022 1.253-2.81 1.951-4.57 1.951c-3.083 0-5.576-2.447-5.576-5.463S9.424 6.34 12.503 6.34a5.67 5.67 0 0 1 4.57 2.342");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ye7uxbcwu {
  fill: var(--svg-color--ffc010, #ffc010);
  d: path("M24 0H0v24h24z");
}

</style>
