<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q-zu2_bmn"/><path class="bq4nprtgq"/><path class="yxf4abbyw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mtrg-background" /></template>
<style>
.bq4nprtgq {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4.842a7.37 7.37 0 0 1 6.737 4.632l-1.263.21A5.865 5.865 0 0 0 12 6.144c-3.276 0-5.962 2.568-5.895 5.856l-1.179 1.116A7.17 7.17 0 0 1 12 4.842M6.648 14.38a5.87 5.87 0 0 0 5.348 3.478c3.313 0 6-2.779 5.899-6.067l1.212-.649A7.163 7.163 0 0 1 12 19.158a7.18 7.18 0 0 1-6.501-4.21z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q-zu2_bmn {
  fill: var(--svg-color--1c2c5f, #1c2c5f);
  d: path("M24 0H0v24h24z");
}

.yxf4abbyw {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 14.526l7.158-5.053l-.421 2.105l4.21-2.105l-.42 2.105L20 9.894l-7.368 3.58l.631-1.896l-4.21 2.106l.42-1.685z");
}

</style>
