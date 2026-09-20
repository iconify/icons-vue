<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="g_bw5bc3i"/><path class="y5qc97gbp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rcn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g_bw5bc3i {
  fill: var(--svg-color--4155ff, #4155ff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y5qc97gbp {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.97 8.777a.5.5 0 0 0-.458-.329a.49.49 0 0 0-.444.28a8 8 0 0 1-.427.8a7.1 7.1 0 0 0-3.397-3.85a7.047 7.047 0 0 0-9.212 2.503a7.15 7.15 0 0 0-1 5.042a9 9 0 0 0-.978 1.623a.488.488 0 1 0 .88.418q.192-.408.431-.796a7.1 7.1 0 0 0 3.393 3.855a7.047 7.047 0 0 0 9.212-2.504a7.14 7.14 0 0 0 1.005-5.041q.575-.762.978-1.623a.5.5 0 0 0 .017-.378m-1.867 3.224a6.16 6.16 0 0 1-1.534 4.063a6.09 6.09 0 0 1-10.492-2.592a9.1 9.1 0 0 1 4.646-2.814a13.8 13.8 0 0 1 3.045-.467l-1.463 1.467l.694.698l2.646-2.663l-3.015-3.028l-.689.694l1.836 1.85a14.2 14.2 0 0 0-3.29.497c-1.263.334-2.454.89-3.526 1.636a9 9 0 0 0-1.058.89l-.004-.236a6.091 6.091 0 0 1 12.017-1.476a9.03 9.03 0 0 1-4.641 2.819c-.996.266-2.014.426-3.046.466l1.459-1.467l-.694-.698l-2.641 2.66l3.023 3.037l.69-.694l-1.837-1.85a14.5 14.5 0 0 0 3.29-.497a11.1 11.1 0 0 0 3.522-1.636a8.5 8.5 0 0 0 1.062-.89z");
}

</style>
