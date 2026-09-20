<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jfe43socm"/><path clip-rule="evenodd" class="vw3z6y51h"/><path clip-rule="evenodd" class="l777bubvn"/><path class="vcrbltpgf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mft-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jfe43socm {
  fill: var(--svg-color--da1157, #da1157);
  d: path("M24 0H0v24h24z");
}

.l777bubvn {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12c0 2.651-2.095 4.8-4.68 4.8s-4.68-2.149-4.68-4.8s2.095-4.8 4.68-4.8S20 9.35 20 12m-2.64 0c0 1.156-.914 2.093-2.04 2.093c-1.127 0-2.04-.937-2.04-2.092s.913-2.092 2.04-2.092c1.126 0 2.04.936 2.04 2.092");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vcrbltpgf {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.632 11.968c0-1.72.9-2.957 1.368-3.36a4.66 4.66 0 0 1 1.384 3.36A5.13 5.13 0 0 1 12 15.391a4.88 4.88 0 0 1-1.368-3.424");
}

.vw3z6y51h {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.36 12c0 2.651-2.095 4.8-4.68 4.8S4 14.651 4 12s2.095-4.8 4.68-4.8s4.68 2.15 4.68 4.8m-2.64 0c0 1.156-.914 2.093-2.04 2.093c-1.127 0-2.04-.937-2.04-2.092s.913-2.092 2.04-2.092c1.126 0 2.04.936 2.04 2.092");
}

</style>
