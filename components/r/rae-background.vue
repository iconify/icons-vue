<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="csjz_0zjw"/><path class="hl7i__-af"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rae-background" /></template>
<style>
.csjz_0zjw {
  fill: var(--svg-color--383f51, #383f51);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hl7i__-af {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.848 11.58L4 9.15l6.737-3.887zm8.304 0L20 9.15l-6.737-3.887zm-7.1.42L12 5.263L14.947 12L12 18.737z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
