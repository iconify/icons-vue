<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="i4sxnka0v"/><path class="vbt6gpbuk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vtho-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i4sxnka0v {
  fill: var(--svg-color--c1cddc, #c1cddc);
  d: path("M17.053 4h-2.19l-5.02 6.93h1.575L7.402 20l9.264-10.526H12.74z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vbt6gpbuk {
  fill: var(--svg-color--2a5285, #2a5285);
  d: path("M6.947 12.842L10.37 4h4.58l-3.91 6.316h3.498L7.385 20l2.985-7.158z");
}

</style>
