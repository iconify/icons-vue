<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="srboc9ugm"/><path class="w87corefq"/><path clip-rule="evenodd" class="rvwypdbzg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xno-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rvwypdbzg {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.424 9.139a2.569 2.569 0 1 0 0-5.138a2.569 2.569 0 0 0 0 5.138M6.576 9.15a2.57 2.57 0 1 0 0-5.138a2.57 2.57 0 0 0 0 5.138m0 10.849a2.568 2.568 0 0 0 1.817-4.386a2.57 2.57 0 0 0-3.634 0A2.57 2.57 0 0 0 6.576 20m13.418-2.57a2.57 2.57 0 0 1-2.57 2.57a2.568 2.568 0 0 1-1.816-4.386a2.569 2.569 0 0 1 4.386 1.817");
}

.srboc9ugm {
  fill: var(--svg-color--092049, #092049);
  d: path("M24 0H0v24h24z");
}

.w87corefq {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.564 4.808L4.873 15.542l3.209 3.992l11.14-11.138z");
}

</style>
