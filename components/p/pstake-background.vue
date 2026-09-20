<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f_q5c8b0v"/><path class="o2w5macgi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pstake-background" /></template>
<style>
.f_q5c8b0v {
  fill: var(--svg-color--e50913, #e50913);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.o2w5macgi {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.343 10.5h-3.17c0-.46-.265-1.5-1.33-1.5s-1.35.815-1.34 1.2c0 1 1.635 1.67 2.43 1.885c3.085.91 3.65 2.73 3.55 3.525c.16 1.465-.5 4.39-4.4 4.39s-4.68-2.63-4.58-4h3c0 .465.285 1.5 1.58 1.5c1.035 0 1.4-1.15 1.42-1.55c.08-.385-.45-1.1-2.955-1.815c-3.14-.895-3.035-3.1-3.035-3.695c0-.6.015-3.94 4.415-3.94c3.52 0 4.41 2.685 4.415 4M7.505 4h9v2h-9z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
