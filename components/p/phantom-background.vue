<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t3bvgzbya"/><path class="iv_rbbbxu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:phantom-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iv_rbbbxu {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.893 18.4c2.042 0 3.576-1.706 4.492-3.054a2.5 2.5 0 0 0-.173.883c0 .787.47 1.348 1.398 1.348c1.275 0 2.636-1.074 3.341-2.23q-.075.25-.074.464c0 .55.322.895.978.895c2.066 0 4.145-3.52 4.145-6.597C20 7.711 18.738 5.6 15.57 5.6C10.002 5.6 4 12.137 4 16.36c0 1.658.928 2.04 1.893 2.04m7.759-8.553c0-.597.347-1.014.854-1.014c.495 0 .841.417.841 1.014c0 .596-.346 1.026-.841 1.026c-.508 0-.854-.43-.854-1.026m2.648 0c0-.597.347-1.014.854-1.014c.495 0 .841.417.841 1.014c0 .596-.346 1.026-.841 1.026c-.507 0-.854-.43-.854-1.026");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t3bvgzbya {
  fill: var(--svg-color--ab9ff2, #ab9ff2);
  d: path("M24 0H0v24h24z");
}

</style>
