<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="ugcvxxvof"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wxt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ugcvxxvof {
  fill: var(--svg-color--c9ffc6, #c9ffc6);
  d: path("m17.843 7.368l-1.77 6.316l-1.725-6.316h-3.044l-1.701 6.316l-1.78-6.316H5.665l.593 2.105H4v1.685h2.749l.403 1.263H4v1.684h3.65l.723 2.526h2.576l1.892-7.158l1.871 7.158h2.576L20 7.368z");
}

</style>
