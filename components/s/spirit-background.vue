<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="i0hrx3b4j"/><path class="sjj6wcc5p"/><path clip-rule="evenodd" class="nxedtdq5v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:spirit-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i0hrx3b4j {
  fill: var(--svg-color--28404e, #28404e);
  d: path("M24 0H0v24h24z");
}

.nxedtdq5v {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.002 4.001c-2.099-.047-6.288 1.3-6.288 7.092v.005C4.714 18.34 9.92 20 11.541 20c.35-.019 1.12-.222 1.428-.86c.383-.804 1.002-1.088 1.74-1.088c.737 0 1.333-.293 1.333-1.319a1.825 1.825 0 0 1 1.858-1.877c1.111 0 1.385-.614 1.385-1.215c-.808-.104-2.42-.884-2.42-3.21c0-3.418-1.73-6.43-5.863-6.43M8.26 10.856a1.891 1.891 0 1 0 0-3.782a1.891 1.891 0 0 0 0 3.782m4.728 0a1.891 1.891 0 1 0 0-3.783a1.891 1.891 0 0 0 0 3.783");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sjj6wcc5p {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.261 7.547h-.019a1.41 1.41 0 0 0-1.4 1.418a1.41 1.41 0 0 0 1.42 1.418zm4.727 0h-.019a1.41 1.41 0 0 0-1.4 1.418a1.41 1.41 0 0 0 1.42 1.418z");
}

</style>
