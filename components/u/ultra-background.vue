<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d41fa4r1t"/><path class="w8lo4tbht"/><path class="k81hkjgyx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ultra-background" /></template>
<style>
.d41fa4r1t {
  fill: var(--svg-color--6f3de0, #6f3de0);
  d: path("M0 0h24v24H0z");
}

.ft5dv1b6b {
  fill: none;
}

.k81hkjgyx {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.4 4v8.001a1.6 1.6 0 1 0 3.2 0V4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w8lo4tbht {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4v7.999a8 8 0 1 0 16 0V4h-3.2v7.999a4.8 4.8 0 1 1-9.6 0V4z");
}

</style>
