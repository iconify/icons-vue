<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGVGPi5cWS)" class="iy8slbgfl"/><defs><linearGradient id="SVGVGPi5cWS" x1="16.661" x2="7.098" y1="5.009" y2="19.595" gradientUnits="userSpaceOnUse"><stop class="os6c1bb_i"/><stop offset="1" class="ezqfkqbwd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xy" /></template>
<style>
.ezqfkqbwd {
  stop-color: var(--svg-color--1033b3, #1033b3);
}

.ft5dv1b6b {
  fill: none;
}

.iy8slbgfl {
  d: path("m3 17.906l6.187-6.75l-4.5-5.062h6.188l1.688 1.687L16.5 3.844H21L5.813 20.156zm9.844-3.375l1.406 1.688h6.469l-4.5-5.063z");
}

.os6c1bb_i {
  stop-color: var(--svg-color--13c0e4, #13c0e4);
}

</style>
