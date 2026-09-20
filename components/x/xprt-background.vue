<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="o8redqblj"/><path clip-rule="evenodd" class="jp3-r_bdt"/><path class="set9nhbml"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xprt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jp3-r_bdt {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7 7v13h3v-4.5h2.725c2.36 0 4.275-1.9 4.275-4.25S15.085 7 12.725 7zm3 5.905h2.115a1.66 1.66 0 0 0 1.665-1.655a1.66 1.66 0 0 0-1.665-1.655H10z");
}

.o8redqblj {
  fill: var(--svg-color--e80813, #e80813);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.set9nhbml {
  fill: var(--svg-color--fff, #fff);
  d: path("M7 4h10v2H7z");
}

</style>
