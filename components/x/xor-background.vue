<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vgp810_8q"/><path class="nptnr33al"/><path class="h_9w6kw1x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xor-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h_9w6kw1x {
  fill: var(--svg-color--fff, #fff);
  d: path("M7 12v-1.5h4.5v-1H7V8h10v1.5h-4.5v1H17V12h-4.34l4.248 6.319A8 8 0 0 0 20 11.999A8 8 0 0 0 12 4a8 8 0 0 0-4.908 14.319l4.249-6.32z");
}

.nptnr33al {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.191 19.035A7.95 7.95 0 0 0 12 20a7.94 7.94 0 0 0 3.808-.965L12 13.362z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vgp810_8q {
  fill: var(--svg-color--e3232c, #e3232c);
  d: path("M24 0H0v24h24z");
}

</style>
