<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jqtvfn9uf"/><path class="bfxgv2bkb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:num-background" /></template>
<style>
.bfxgv2bkb {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.333 5.6v7.466l5.334 5.334v-7.467zM20 5.6h-5.333v5.333L18.4 14.65l-3.733 3.75H20zm-10.667 0H4v12.8h5.333v-5.334L5.6 9.333z");
}

.ft5dv1b6b {
  fill: none;
}

.jqtvfn9uf {
  fill: var(--svg-color--0000d8, #0000d8);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
