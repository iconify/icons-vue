<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="m0hm08b9k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rdn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m0hm08b9k {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.86 12.889C13.894 7.804 9.079 4.844 6.668 4h6.775c3.212 2.36 3.931 6.909 3.89 8.889zm-4.97-2.667V20l4.444-2.475z");
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
