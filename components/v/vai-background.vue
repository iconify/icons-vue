<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGmhOpqdpr)" class="r4i437pya"/><path class="r7h8g9b2e"/></g><defs><linearGradient id="SVGmhOpqdpr" x1="18.773" x2="9.6" y1="7.708" y2="16.3" gradientUnits="userSpaceOnUse"><stop class="u9q0gsbru"/><stop offset=".28" class="ivgo_nzpj"/><stop offset=".57" class="m5_qrb4tl"/><stop offset="1" class="y0atxvdoq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vai-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ivgo_nzpj {
  stop-color: var(--svg-color--5d70f8, #5d70f8);
}

.m5_qrb4tl {
  stop-color: var(--svg-color--5f5bf6, #5f5bf6);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.r7h8g9b2e {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.02 6.296l3.452 3.376a.32.32 0 0 1 0 .456l-3.456 3.384a.336.336 0 0 1-.468 0l-3.453-3.38a.32.32 0 0 1 0-.456l3.457-3.38a.336.336 0 0 1 .468 0m4.216 4.192l3.452 3.38a.32.32 0 0 1 0 .456l-3.456 3.38a.336.336 0 0 1-.468 0l-3.452-3.376a.32.32 0 0 1 0-.456l3.456-3.384a.336.336 0 0 1 .468 0m4.216-4.192l3.452 3.376a.32.32 0 0 1 .071.351a.3.3 0 0 1-.07.105l-3.457 3.384a.336.336 0 0 1-.468 0l-3.452-3.38a.32.32 0 0 1 0-.456l3.456-3.38a.336.336 0 0 1 .468 0");
}

.u9q0gsbru {
  stop-color: var(--svg-color--5c84f9, #5c84f9);
}

.y0atxvdoq {
  stop-color: var(--svg-color--6349f4, #6349f4);
}

</style>
