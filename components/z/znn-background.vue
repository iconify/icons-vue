<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gzeorrb0j"/><path clip-rule="evenodd" class="jui8ae34b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:znn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gzeorrb0j {
  fill: var(--svg-color--00ff65, #00ff65);
  d: path("M24 0H0v24h24z");
}

.jui8ae34b {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M7 4h10v1.92L10.895 10H17v10h-1.81L9 14.7V20H7V9.94L13.255 6H7zm2 8h6v5z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
