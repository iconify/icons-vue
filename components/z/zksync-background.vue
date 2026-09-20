<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="isquf7biw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zksync-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.isquf7biw {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m20 12l-4.539-3.998v2.93l-4.506 2.931l4.506.002V16zM4 12l4.539 4v-2.9l4.475-2.934l-4.473-.001V8z");
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
