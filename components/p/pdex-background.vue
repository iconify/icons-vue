<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c8b1vubah"/><path class="xi1vm7b-r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pdex-background" /></template>
<style>
.c8b1vubah {
  fill: var(--svg-color--e6007a, #e6007a);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xi1vm7b-r {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 18.005v-2.258l-3.75-3.744H14zM4 6.345v2.196l3.814 4.033H10zM6 4h2.187l3.781 3.736L15.715 4H18l-6 6.023zm0 16h2.186l3.781-3.735L15.715 20H18l-6-5.986zm6-6.853a1.143 1.143 0 1 0 0-2.287a1.143 1.143 0 0 0 0 2.287");
}

</style>
