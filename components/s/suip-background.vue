<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gd2qehwal"/><path class="jw0387bfq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:suip-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gd2qehwal {
  fill: var(--svg-color--4ec3c9, #4ec3c9);
  d: path("M24 0H0v24h24z");
}

.jw0387bfq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.897 10.416L16.775 8.3h-.004l-.004-.008a3.72 3.72 0 0 0-2.65-1.09a3.74 3.74 0 0 0-2.123.655a3.73 3.73 0 0 0-2.118-.656a3.74 3.74 0 0 0-2.654 1.095l-2.118 2.115a3.71 3.71 0 0 0 0 5.283a3.73 3.73 0 0 0 2.65 1.095c.767 0 1.499-.231 2.118-.655a3.73 3.73 0 0 0 2.127.651c.767 0 1.498-.227 2.118-.655a3.73 3.73 0 0 0 3.565.38a3.728 3.728 0 0 0 1.218-6.09zM8.72 15.076a2.239 2.239 0 0 1-2.558-3.61l2.118-2.11a2.24 2.24 0 0 1 2.562-.44l-1.498 1.496a3.7 3.7 0 0 0-1.1 2.641c0 .712.2 1.391.568 1.979zm4.864-.44a2.24 2.24 0 0 1-2.45.492a2.237 2.237 0 0 1-.735-3.661l1.598-1.587l1.591 1.587a2.237 2.237 0 0 1 0 3.17zm4.249.012a2.26 2.26 0 0 1-2.662.388a3.7 3.7 0 0 0 .535-2.51a3.7 3.7 0 0 0-1.063-2.114L13.157 8.92l-.008-.008a2.25 2.25 0 0 1 2.558.44h.008v.007l2.115 2.103l.008.012a2.227 2.227 0 0 1 0 3.17z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
