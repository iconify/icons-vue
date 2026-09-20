<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qre1-5b-u"/><path class="kuqz_0icf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zeta-chain-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kuqz_0icf {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.407 15.482v2.127H7.632c.121-1.4.573-2.385 2.135-3.77l6.64-5.665v4.971h2.39V4H5.205v4.559h2.39V6.39h7.22l-6.607 5.64l-.016.014c-2.77 2.452-2.99 4.43-2.99 6.762V20h13.595v-4.517z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qre1-5b-u {
  fill: var(--svg-color--005741, #005741);
  d: path("M24 0H0v24h24z");
}

</style>
