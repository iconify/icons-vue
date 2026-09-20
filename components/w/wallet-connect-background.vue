<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dfs4wvb-i"/><path class="mpfndachg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wallet-connect-background" /></template>
<style>
.dfs4wvb-i {
  fill: var(--svg-color--3b99fc, #3b99fc);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.mpfndachg {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.276 9.076c2.609-2.501 6.84-2.501 9.449 0l.313.3a.31.31 0 0 1 0 .453l-1.074 1.03a.17.17 0 0 1-.236 0l-.432-.414c-1.82-1.745-4.772-1.745-6.592 0l-.463.444a.17.17 0 0 1-.236 0l-1.074-1.03a.31.31 0 0 1 0-.453zm11.67 2.129l.956.916a.31.31 0 0 1 0 .453l-4.31 4.132a.344.344 0 0 1-.473 0l-3.06-2.932a.086.086 0 0 0-.118 0l-3.06 2.932a.344.344 0 0 1-.472 0l-4.311-4.132a.31.31 0 0 1 0-.453l.956-.916a.344.344 0 0 1 .472 0l3.06 2.933a.086.086 0 0 0 .118 0l3.06-2.933a.344.344 0 0 1 .472 0l3.06 2.933a.086.086 0 0 0 .118 0l3.06-2.933a.345.345 0 0 1 .472 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
