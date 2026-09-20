<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bxtpnhb9x"/><path class="b71rfwbdv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tronpad-background" /></template>
<style>
.b71rfwbdv {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.106 17.556a.4.4 0 0 1-.133-.027c-.133-.053-.196-.187-.196-.333v-6.4l-5.613-3.69a.365.365 0 0 1-.151-.4a.37.37 0 0 1 .35-.262H19.64a.36.36 0 0 1 .329.218a.36.36 0 0 1-.063.387l-2.764 3.022a.366.366 0 0 1-.533.046a.365.365 0 0 1-.005-.535l2.209-2.413H5.568l4.738 3.129a.36.36 0 0 1 .165.302v5.667l1.973-2.178V9.262c0-.138.102-.266.227-.324a.36.36 0 0 1 .382.04l2.662 2.062a.36.36 0 0 1 .12.402a.4.4 0 0 1-.075.127l-2.565 2.8v2.827c0 .2-.164.36-.364.36s-.387-.165-.387-.36v-2.04l-2.071 2.28a.36.36 0 0 1-.267.12M13.196 10v3.293l1.76-1.924l-1.756-1.37z");
}

.bxtpnhb9x {
  fill: var(--svg-color--ed1c24, #ed1c24);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
