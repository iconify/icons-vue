<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c7sbsnbbl"/><path class="qpoptryqj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:utk-background" /></template>
<style>
.c7sbsnbbl {
  fill: var(--svg-color--7c4dff, #7c4dff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qpoptryqj {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.86 12L20 8.152l-1.2-2.327l-6.537 2.667a.7.7 0 0 1-.524 0L5.2 5.827L4 8.152L11.14 12L4 15.848l1.2 2.327l6.538-2.667a.7.7 0 0 1 .523 0l6.537 2.668l1.2-2.328z");
}

</style>
