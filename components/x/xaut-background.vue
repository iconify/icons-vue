<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="r352l6bak"/><path clip-rule="evenodd" class="fg1miyb4x"/><path class="bh3xxybmj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xaut-background" /></template>
<style>
.bh3xxybmj {
  fill: var(--svg-color--dda85b, #dda85b);
  d: path("M15.6 7.2H8.4v1.6h2.8v2.8h1.6V8.8h2.8z");
}

.fg1miyb4x {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.006 4.8H6.972L4 11.322l8 7.878l8-7.878zM12.8 12.383c2.27-.095 4.002-.588 4.002-1.183c0-.663-2.15-1.2-4.8-1.2s-4.8.537-4.8 1.2c0 .594 1.729 1.088 3.998 1.183V16h1.6z");
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

.r352l6bak {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 12c2.43 0 4.4-.358 4.4-.8c0-.441-1.97-.8-4.4-.8s-4.4.358-4.4.8s1.97.8 4.4.8");
}

</style>
