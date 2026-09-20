<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ztbfesxjh"/><path clip-rule="evenodd" class="rx0i9mbyj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:scp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rx0i9mbyj {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.5 10.5c0 2.05-1.45 3.5-3.5 3.5H8.5v-3.5C8.5 8.45 9.95 7 12 7s3.5 1.45 3.5 3.5m3 0A6.5 6.5 0 0 1 12 17H8.5v3h-3v-9.5a6.5 6.5 0 1 1 13 0");
}

.ztbfesxjh {
  fill: var(--svg-color--2074ee, #2074ee);
  d: path("M24 0H0v24h24z");
}

</style>
