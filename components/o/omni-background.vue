<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w6v0ffc9v"/><path class="ofc855h2y"/><path clip-rule="evenodd" class="z6tbnrb2c"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:omni-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ofc855h2y {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.5 7.198V4.5h-2.84c1.026.65 2.163 1.706 2.84 2.698M7.416 4.5H4.5v2.767C5.103 6.12 6.232 5.072 7.416 4.5M4.5 16.733V19.5h2.876c-1.029-.661-2.203-1.76-2.876-2.767M16.707 19.5H19.5v-2.698c-.667.977-1.788 2.051-2.793 2.698");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w6v0ffc9v {
  fill: var(--svg-color--1d3f7b, #1d3f7b);
  d: path("M24 0H0v24h24z");
}

.z6tbnrb2c {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.788 20v-.008c4.536 0 8.212-3.579 8.212-7.996C20 7.587 16.324 4 11.788 4C7.565 4.22 4 7.715 4 12s3.565 7.78 7.788 8m.204-14C8.724 6.004 5.995 8.74 6 12.008S8.74 18.004 12.008 18s5.996-2.74 5.992-6.008S15.26 5.995 11.992 6");
}

</style>
