<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kckx8exqg"/><path class="b0fkp-ivh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mint-background" /></template>
<style>
.b0fkp-ivh {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4a8 8 0 0 1 8 8a8 8 0 0 1-8-8m16 16a8 8 0 0 1-8-8a8 8 0 0 1 8 8m-8-8a4 4 0 0 1 4-4a4 4 0 0 1-4 4m0 0a4 4 0 0 1-4 4a4 4 0 0 1 4-4");
}

.ft5dv1b6b {
  fill: none;
}

.kckx8exqg {
  fill: var(--svg-color--30bf54, #30bf54);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
