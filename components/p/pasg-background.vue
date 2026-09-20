<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="c9ckuqbst"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pasg-background" /></template>
<style>
.c9ckuqbst {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.501 12A7.5 7.5 0 1 1 4.5 12a7.5 7.5 0 0 1 15.002 0M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-2.09 0a5.91 5.91 0 1 1-11.82 0a5.91 5.91 0 0 1 11.822 0m1.149 0a7.06 7.06 0 1 1-14.12 0a7.06 7.06 0 0 1 14.12 0M9.412 9.647a1.177 1.177 0 0 0-1.177 1.176v2.354a1.176 1.176 0 1 0 2.353 0v-1.003h-.847l.847-.955v-.396a1.176 1.176 0 0 0-1.176-1.176m4 1.176a1.177 1.177 0 0 1 2.353 0v.396l-.847.96h.847v.998a1.176 1.176 0 1 1-2.353 0z");
}

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

</style>
