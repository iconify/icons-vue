<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gbv_5qc6o"/><path clip-rule="evenodd" class="aei94p9lz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:odos-background" /></template>
<style>
.aei94p9lz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m7.456 6.463l1.099 1.133a5.577 5.577 0 0 1 7.75.841l-1.108 1.136a4.015 4.015 0 0 1-5.544 5.691l-.563.585a4.823 4.823 0 0 0 7.14-6.17l.55-.57a5.58 5.58 0 0 1-.477 6.453l.565.581a6.396 6.396 0 0 0-8.212-9.598l-.55-.559a7.1 7.1 0 0 1 3.89-1.152c1.66-.01 3.27.568 4.544 1.63l.565-.58A7.964 7.964 0 0 0 6.023 17.268l.565-.58a7.147 7.147 0 0 1 .868-10.226m3.08 4.394h3.34l-1.68 3.192zm-1.333-.81l2.793 5.365l2.793-5.364zm8.2-2.74l.566-.58h.004A7.963 7.963 0 0 1 6.89 18.111l.566-.581a7.14 7.14 0 0 0 8.426.482l-.55-.559a6.395 6.395 0 0 1-8.21-9.598l.57.584a5.58 5.58 0 0 0-.477 6.453l.55-.57a4.824 4.824 0 0 1 7.137-6.178l-.573.587a3.88 3.88 0 0 0-2.334-.752a4.016 4.016 0 0 0-3.202 6.446l-.568.584l-.537.55a5.58 5.58 0 0 0 7.75.84l.565.583l.535.55a7.15 7.15 0 0 0 .865-10.226");
}

.ft5dv1b6b {
  fill: none;
}

.gbv_5qc6o {
  fill: var(--svg-color--ff5100, #ff5100);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
