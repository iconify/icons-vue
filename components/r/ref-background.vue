<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="obzfj6bpz"/><path clip-rule="evenodd" class="d9tbrf2au"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ref-background" /></template>
<style>
.d9tbrf2au {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.897 5.263H8.072L4 12l4.072 6.737h7.825L20 12zm-1.884 2.526H8.631v2.105h4.21l-4.21 3.356v2.959l6.948-5.59zm-2.37 6.59l1.724-1.409l2.843 3.238h-3.04z");
}

.ft5dv1b6b {
  fill: none;
}

.obzfj6bpz {
  fill: var(--svg-color--f38f31, #f38f31);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
