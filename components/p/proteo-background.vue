<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGia0OQcXF" class="yb-0vcsdm"/></defs><g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="j3sgzyqhu"/><use href="#SVGia0OQcXF"/><use href="#SVGia0OQcXF"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:proteo-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j3sgzyqhu {
  fill: var(--svg-color--d7a012, #d7a012);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yb-0vcsdm {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.307 6.543l-3.36 5.036L12 20l5.052-8.421l-3.36-5.036l.994 5.036h1.184l-3.449 6.316v-6.316h1.082l-1.486-7.558L12 4l-.017.021l-1.486 7.558h1.082v6.316l-3.453-6.316h1.188z");
}

</style>
