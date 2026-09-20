<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bkh2clbho"/><path class="of75-pz8t"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rbif-background" /></template>
<style>
.bkh2clbho {
  fill: var(--svg-color--0095f1, #0095f1);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.of75-pz8t {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.5 20H11V4H9.875c.16 4.33-.3 13.595-3.375 16m11 0H13V4h1.125c-.16 4.33.3 13.595 3.375 16");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
