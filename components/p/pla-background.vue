<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fslisbb9i"/><path class="tq2hlibyn"/><path class="vkvp1zb3c"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pla-background" /></template>
<style>
.fslisbb9i {
  fill: var(--svg-color--0079f0, #0079f0);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tq2hlibyn {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.502 6.251a1.666 1.666 0 0 1 2.998 0l5.607 11.642a.555.555 0 0 1-.5.794H5.394a.556.556 0 0 1-.5-.794z");
}

.vkvp1zb3c {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.752 5.89a2.498 2.498 0 0 1 4.496 0l5.613 11.636a1.387 1.387 0 0 1-1.249 1.993H5.388a1.387 1.387 0 0 1-1.25-1.993L9.747 5.89zm2.997.721a.83.83 0 0 0-1.191-.342a.83.83 0 0 0-.307.342L5.832 17.854h12.33L12.744 6.617z");
}

</style>
