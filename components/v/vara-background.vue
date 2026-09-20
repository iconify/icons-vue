<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jaden4byo"/><path class="f9xq-bb1q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vara-background" /></template>
<style>
.f9xq-bb1q {
  fill: var(--svg-color--000, #000);
  d: path("M17.277 9.64L12.8 3H9.638l7.639 11.33v4.325L6.724 3H3.563l12.133 18h4.741V3h-3.16z");
}

.ft5dv1b6b {
  fill: none;
}

.jaden4byo {
  fill: var(--svg-color--00ffc4, #00ffc4);
  d: path("M0 0h24v24H0z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
