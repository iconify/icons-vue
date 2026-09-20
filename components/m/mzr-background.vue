<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="g5jpit1rl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mzr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g5jpit1rl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.467 20V4L12 10.08L4.533 4v16l3.734-3.115v-5.648L12 14.464l3.733-3.227v5.654zM12 12.725L7.008 8.523v7.605l-1.157.87V6.751L12 11.782zm0 0l4.976-4.202v7.605l1.173.87V6.751L12 11.782zm-2.133 4.31l2.138 2.005l2.128-2.005v-2.47l-2.128 2.027l-2.138-2.032z");
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
