<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kw3q7qbyj"/><path class="xjuidy4tq"/><path class="m3fak-vck"/><path class="jepr8tl-k"/><path class="whgeejbwg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tkp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jepr8tl-k {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.88 9.289l-1.87.727a5.79 5.79 0 0 1-2.624 7.049a5.64 5.64 0 0 1-7.268-1.623a5.806 5.806 0 0 1 .548-7.515a5.636 5.636 0 0 1 7.429-.521l1.266-1.568a7.61 7.61 0 0 0-8.073-.81A7.79 7.79 0 0 0 4 12c0 3.108 1.833 5.92 4.658 7.145a7.61 7.61 0 0 0 8.32-1.518A7.84 7.84 0 0 0 18.88 9.29");
}

.kw3q7qbyj {
  fill: var(--svg-color--ffaf14, #ffaf14);
  d: path("M24 0H0v24h24z");
}

.m3fak-vck {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.16 9.884a3.9 3.9 0 0 0-1.304-1.77l-2.537 3.237l3.84-1.463z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.whgeejbwg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.208 5.495a8 8 0 0 0-.763-.618L16.16 6.331a5.3 5.3 0 0 1 1.943 2.423L20 8.09a7.2 7.2 0 0 0-1.792-2.59z");
}

.xjuidy4tq {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.42 12.11l2.55-3.227a3.81 3.81 0 0 0-5.01.375a3.92 3.92 0 0 0-.352 5.074a3.81 3.81 0 0 0 4.91 1.079a3.91 3.91 0 0 0 1.76-4.759l-3.859 1.463z");
}

</style>
