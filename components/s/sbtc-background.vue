<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nydu95obq"/><path class="kjh91zbum"/><path class="ay6kvke4l"/><path clip-rule="evenodd" class="bepq_wb6k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sbtc-background" /></template>
<style>
.ay6kvke4l {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.864 11H11v.5h1.864c.045-.015.136-.083.136-.241c0-.159-.091-.24-.136-.259m0 1.5H11v.5h1.864c.045-.014.136-.083.136-.241c0-.159-.091-.239-.136-.259");
}

.bepq_wb6k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16 12a4 4 0 1 1-8 0a4 4 0 0 1 8 0m-6 2v-4h2.898c.705 0 1.101.665 1.101 1.197c0 .425-.183.695-.274.776c.22.221.274.624.274.797c.019.763-.628 1.23-.98 1.23z");
}

.ft5dv1b6b {
  fill: none;
}

.kjh91zbum {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20a8 8 0 0 0 6.93-12h-3.929A4.99 4.99 0 0 1 17 11.999a5 5 0 0 1-4.992 4.999l.004.002H5.755A7.99 7.99 0 0 0 12 20m-6.93-4a8 8 0 0 1 13.175-9H12a5 5 0 0 0-2.998 9z");
}

.nydu95obq {
  fill: var(--svg-color--4e4294, #4e4294);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
