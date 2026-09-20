<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lbahwbbhj"/><path class="ujua6y4cr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:top-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lbahwbbhj {
  fill: var(--svg-color--f8cf03, #f8cf03);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ujua6y4cr {
  fill: var(--svg-color--000, #000);
  d: path("M5.78 4.877a1.78 1.78 0 0 0 0 3.562h.891a1.78 1.78 0 0 0 0-3.562zm6.305 0h6.162a1.781 1.781 0 0 1 0 3.562h-3.835a.617.617 0 0 0-.617.617v8.282a1.786 1.786 0 1 1-3.572 0c.004-2.822.01-8.239.01-10.716c0-.683.358-1.745 1.852-1.745");
}

</style>
