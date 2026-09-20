<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rlgb7db0c"/><path class="nhbgvbbke"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:verse-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nhbgvbbke {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.358 7.294l-1.46-2.353H4l7.93 14.118l1.482-2.47l-5.266-9.295zm-2.26 1.412h2.862l1.143 1.901l3.036-5.666H20l-5.896 10.485z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rlgb7db0c {
  fill: var(--svg-color--0085ff, #0085ff);
  d: path("M24 0H0v24h24z");
}

</style>
