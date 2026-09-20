<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gj2gsacka"/><path class="ogryo65_i"/><path class="xba_ndbuz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wndr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gj2gsacka {
  fill: var(--svg-color--ef4035, #ef4035);
  d: path("M24 0H0v24h24z");
}

.ogryo65_i {
  fill: var(--svg-color--fff, #fff);
  d: path("m7.302 6.316l2.99 1.655c-.287.273-.856 1.031-.856 1.86c0 .826.569 1.584.855 1.858h1.07L12 12.93l.64-1.242h1.07c.21-.274.681-1.032.854-1.857c.168-.83-.497-1.588-.855-1.861l2.99-1.655l1.498 1.655l-2.353 1.86l2.779-1.241c.533.414.91.998 1.07 1.654l-3.205 1.444l3.419-.825c.168.497.067 1.449 0 1.861l-3.209.62h2.99a5.78 5.78 0 0 1-2.775 2.892c-.64-.687-2.05-2.021-2.564-1.857s.783 2.274 1.495 3.305c-.51-.497-1.495-.897-1.92-1.032l-.644-2.067v2.063h-1.066L12 14.584l-.21 2.063h-.86v-2.063l-.64 2.063c-.513 0-1.583.758-2.08 1.036c.64-.897 1.781-2.977 1.44-3.305c-.34-.333-1.996 1.099-2.779 1.857l-2.564-2.889h3.204l-3.419-.618c-.168-.83-.071-1.588 0-1.862l3.634.826l-3.419-1.444a4.1 4.1 0 0 1 1.07-1.862l2.778 1.449l-2.353-1.861a6.5 6.5 0 0 1 1.499-1.66");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xba_ndbuz {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 12.518l-.429-1.036h-1.28c.514-.825.64-2.408.64-3.099l2.139.826H12c.211.21 1.07.21 1.28.21c.215 0 .855 0 .855.413c0 .328-.282.686-.425.825c-.286-.345-.939-.994-1.284-.825c-.337.164.572 1.17 1.07 1.65h-1.07z");
}

</style>
