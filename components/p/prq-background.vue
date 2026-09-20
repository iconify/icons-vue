<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ee_ajttwx"/><path class="hzjv1u92s"/><path class="jt9ddkzbt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:prq-background" /></template>
<style>
.ee_ajttwx {
  fill: var(--svg-color--005cc7, #005cc7);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hzjv1u92s {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.015 11.5A8 8 0 0 1 12 4v4h3v-.5h1.5V9H15v-.5h-3V12h3.5v3H15v.5H9V15h-.5V9H9V7.5H7.5V9H8v2.5z");
}

.jt9ddkzbt {
  fill: var(--svg-color--fff, #fff);
  d: path("M15 16.5V16h-2.5v3.985A8 8 0 0 0 20 12h-4v3h.5v1.5zM7.5 15H8v-3H4a8 8 0 0 0 8 8v-4H9v.5H7.5z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
