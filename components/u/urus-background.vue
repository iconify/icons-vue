<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bebri1jkp"/><path class="l0hc_obne"/><path class="giufrob_b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:urus-background" /></template>
<style>
.bebri1jkp {
  fill: var(--svg-color--82858e, #82858e);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.giufrob_b {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.199 15.8c0 .64.532.8.8.8c.4 0 .724-.2.8-.8c.2-1.6 1-3.4 1.2-3.999s1.2-.8 1.2-1c0-.336-.4 0-.4-.4c0-.48.531-.868.8-1h1.999l2.136-1.78c.036-.028 0-.088-.044-.064l-2.092 1.044h-2c-.268 0-.856.128-1 .2c-.4.2-2.2 1-2.6 1s-2.599-1-2.599-1s-.632-.2-1-.2H6.8l-2.607-1.12c-.04-.015-.08.037-.044.064c.62.616 1.904 1.856 2.052 1.856H8c.4 0 1.2.6 1.2 1s-.4.2-.4.4s.8.6 1.199 1c.4.4 1.2 3.2 1.2 4");
}

.l0hc_obne {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.29 8.321l1.548-.904c.048-.032.096-.012.124.024l.012.004c.032.04.04.1-.008.148L18.378 9.29c-.204.22-.472.36-.76.404l-1.4.208a1.2 1.2 0 0 0-.6.272l-.36.308l.193.088c.288.132.4.5.24.788l-2.76 4.955c-.132.228-.624.288-.932.288c-.296 0-.8-.056-.928-.288l-2.763-4.96a.563.563 0 0 1 .24-.783l.196-.088l-.364-.308a1.23 1.23 0 0 0-.6-.272l-1.4-.208a1.3 1.3 0 0 1-.76-.404L4.032 7.593a.11.11 0 0 1-.008-.148h.016l-.004-.004c.028-.04.076-.056.124-.024l1.548.904c.368.216.78.28 1.2.28h1.38a3.2 3.2 0 0 1 1.2.292l.791.332c.56-.04 1.16-.152 1.72-.152s1.16.116 1.72.152l.792-.332a3.2 3.2 0 0 1 1.2-.292h1.38a2.3 2.3 0 0 0 1.2-.28");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
