<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dh7siugbb"/><path clip-rule="evenodd" class="i-i0-cl-u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:oeth-background" /></template>
<style>
.dh7siugbb {
  fill: var(--svg-color--e5f1fe, #e5f1fe);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.i-i0-cl-u {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0M8.612 8.73A4.7 4.7 0 0 0 7.294 12a4.696 4.696 0 0 0 4.047 4.706l1.021-1.44h-.007l1.998-2.795L12 13.915l-2.353-1.444l2.005 2.807A3.245 3.245 0 0 1 8.706 12a3.29 3.29 0 0 1 2.122-3.078l1.002-1.628a4.7 4.7 0 0 0-3.218 1.437m6.747 6.566a4.7 4.7 0 0 1-3.27 1.41l1.224-1.685a3.294 3.294 0 0 0-1.01-6.301l2.05 3.28L12 13.412L9.647 12l2.044-3.27h-.002l.87-1.436A4.673 4.673 0 0 1 16.707 12a4.7 4.7 0 0 1-1.347 3.296");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
