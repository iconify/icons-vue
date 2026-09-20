<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG2UecDcwB)" class="r4i437pya"/><path class="nd65k923p"/><path class="p0ii4cikj"/></g><defs><linearGradient id="SVG2UecDcwB" x1="14.32" x2="14.32" y1="4.001" y2="15.315" gradientUnits="userSpaceOnUse"><stop offset=".15" class="hvxog_7xt"/><stop offset=".57" class="f8axk9tue"/><stop offset="1" class="fuk6rxy1d"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zano-background" /></template>
<style>
.f8axk9tue {
  stop-color: var(--svg-color--498cfe, #498cfe);
}

.ft5dv1b6b {
  fill: none;
}

.fuk6rxy1d {
  stop-color: var(--svg-color--4a8ffd, #4a8ffd);
}

.hvxog_7xt {
  stop-color: var(--svg-color--19cfd8, #19cfd8);
}

.nd65k923p {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.4 4h1.85c.64 0 1.175 0 1.61.035a3.4 3.4 0 0 1 1.31.335a3.36 3.36 0 0 1 1.465 1.47c.21.42.29.855.33 1.315c.035.44.035.98.035 1.62v1.95c0 .64 0 1.18-.035 1.62a3.5 3.5 0 0 1-.33 1.315a3.37 3.37 0 0 1-1.465 1.475c-.415.21-.85.29-1.31.33c-.435.035-.97.035-1.605.035H9.71a.975.975 0 0 1-.685-1.65l4.5-4.965l1.38 1.36l-2.89 3.255h3.2c1.155 0 2.665.19 2.785-1.315v-4.87c-.065-.785-.485-1.25-1.3-1.315h-4.77c-.79.065-1.325.48-1.38 1.265c-.025.355-.06.87-.05 1.565v.815l-2 .025v-.84c-.01-.65 0-1.19.03-1.635c.035-.465.11-.905.32-1.33a3.7 3.7 0 0 1 1.6-1.49c.42-.22.86-.3 1.32-.34C12.215 4 12.755 4 13.395 4z");
}

.p0ii4cikj {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.3 18h4.825c.78-.06 1.315-.545 1.375-1.32V15.5h2v1.325a3.65 3.65 0 0 1-2.025 2.87c-.385.175-.785.245-1.205.275c-.4.03-.89.03-1.465.03h-2.06c-.635 0-1.17 0-1.605-.035a3.4 3.4 0 0 1-1.31-.335a3.36 3.36 0 0 1-1.465-1.47a3.5 3.5 0 0 1-.33-1.315C4 16.4 4 15.865 4 15.23v-1.97c0-.64 0-1.175.035-1.615c.04-.46.12-.9.33-1.315c.32-.634.833-1.15 1.465-1.475c.415-.21.85-.29 1.31-.33c.435-.035.97-.025 1.605-.025h5.545c.53 0 .965.425.965.96s-.435 1.04-.97 1.04h-5.5c-.685 0-1.14 0-1.49.03c-.78.065-1.23.495-1.295 1.275v4.88c.065.78.515 1.25 1.3 1.315");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
