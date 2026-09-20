<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pdmqc-bho"/><path class="yyoo_xbbf"/><path class="ae9x8mbpv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nord-background" /></template>
<style>
.ae9x8mbpv {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.626 15.675a.67.67 0 0 1 0-.95l3.899-3.9a.67.67 0 0 1 .95 0l3.9 3.9c.26.26.26.685 0 .95l-3.9 3.9a.676.676 0 0 1-.95 0z");
}

.ft5dv1b6b {
  fill: none;
}

.pdmqc-bho {
  fill: var(--svg-color--00dd9a, #00dd9a);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yyoo_xbbf {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.798 12.357a.64.64 0 0 0 0-.932l-7.313-7.003a.713.713 0 0 0-.974 0L4.2 11.425a.64.64 0 0 0 0 .932l1.052 1.006a.713.713 0 0 0 .974 0l5.284-5.065a.713.713 0 0 1 .978 0l5.294 5.056c.27.26.703.26.973 0z");
}

</style>
