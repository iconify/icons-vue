<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="yg146ubev"/><path class="p9a9vgb1y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tifi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p9a9vgb1y {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 14.4v-.16L9.7 8.4h2.64l2.06 2.128l-1.356 1.42l-2.02-2.116l-4.4 4.568zm16-4.8v.16l-5.7 5.84h-2.64L9.6 13.472l1.356-1.42l2.02 2.116l4.4-4.568z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yg146ubev {
  fill: var(--svg-color--00a3ff, #00a3ff);
  d: path("M24 0H0v24h24z");
}

</style>
