<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="sgkg00bvr"/><path clip-rule="evenodd" class="rh431cczv"/><path clip-rule="evenodd" class="k6k249buq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xna-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k6k249buq {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.75 4h.504A8.024 8.024 0 0 1 20 11.755v.5a8.014 8.014 0 0 1-7.713 7.74l-.042.005h-.494A8.024 8.024 0 0 1 4 12.259v-.518A7.986 7.986 0 0 1 11.75 4m7.61 8a7.36 7.36 0 1 1-14.72 0a7.36 7.36 0 0 1 14.72 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rh431cczv {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.353 8.594v5.049l-.037.01h-.005l-4.273-5.695a.08.08 0 0 1-.014-.056A1.446 1.446 0 0 0 7.68 6.504a1.435 1.435 0 0 0-.155 2.024a.13.13 0 0 1 .028.08v6.795l-.014.042l-.094.132a1.43 1.43 0 0 0 .89 2.24a1.42 1.42 0 0 0 1.548-.73a1.43 1.43 0 0 0-.198-1.637l-.014-.014c-.01-.01-.024-.024-.024-.033V11.05c0-.038.033-.038.052-.01l4.23 5.62c.053.07.08.15.11.235l.07.164a1.435 1.435 0 0 0 1.562.753a1.43 1.43 0 0 0 .81-2.343a.12.12 0 0 1-.029-.075V8.608q0-.042.028-.076a1.4 1.4 0 0 0 .344-1.073a1.44 1.44 0 1 0-2.494 1.102l.01.009c.009.005.018.014.018.024zM9.573 7.59a.96.96 0 1 1-1.92 0a.96.96 0 0 1 1.92 0m5.816.96a.96.96 0 1 0 .134-1.914a.96.96 0 0 0-.134 1.914m-5.817 7.86a.96.96 0 1 1-1.919 0a.96.96 0 0 1 1.92 0m5.817.955a.96.96 0 1 0 .134-1.913a.96.96 0 0 0-.134 1.913");
}

.sgkg00bvr {
  fill: var(--svg-color--460063, #460063);
  d: path("M24 0H0v24h24z");
}

</style>
