<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ps037gbou"/><path class="wqsi4zbrw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rif-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ps037gbou {
  fill: var(--svg-color--149dd9, #149dd9);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wqsi4zbrw {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.445 5.333h1.333v4.89h-1.334zm2.222 2.223H16v4h-1.333zm2.222 2.666h1.333v1.334H16.89zm1.778 0H20v1.334h-1.333zm0 2.223v1.333h-4.89v-1.334zm-2.223 2.222V16h-4v-1.333zm-2.666 2.222v1.333h-1.334V16.89zm0 1.778V20h-1.334v-1.333zm-2.222 0h-1.334v-4.89h1.334zm-2.223-2.223H8v-4h1.333zm-2.222-2.666H5.778v-1.334H7.11zm-1.778 0H4v-1.334h1.333zm0-2.222v-1.334h4.89v1.334zm2.223-2.223V8h4v1.333zm2.666-2.222V5.778h1.334V7.11zm0-1.778V4h1.334v1.333z");
}

</style>
