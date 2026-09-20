<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="woz63cc6o"/><path class="sy8gvm7lb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rei-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sy8gvm7lb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.342 11.396c0 .333-.3.603-.67.603h-2.014v-1.205h2.013c.37 0 .67.27.67.602M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-5.065 1.646c.67-.552 1.094-1.343 1.094-2.223c0-1.666-1.503-3.016-3.356-3.016h-4.7v7.19h2.685v-1.164h2.035l.7 1.16h2.634z");
}

.woz63cc6o {
  fill: var(--svg-color--2116e5, #2116e5);
  d: path("M24 0H0v24h24z");
}

</style>
