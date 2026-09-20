<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="l0umi4r1x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vlx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l0umi4r1x {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.294 10.118L12 16l-3.294-5.882zm2.824-1.882H5.882L12 19.059zM4 4.94l1.176 1.883h13.648L20 4.94z");
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
