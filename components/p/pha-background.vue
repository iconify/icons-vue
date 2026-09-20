<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="r9-vg5b5h"/><path clip-rule="evenodd" class="ev8opxb3u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pha-background" /></template>
<style>
.ev8opxb3u {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4 4h12.571v3.429H20V12h-3.429V7.429H7.43V12H4zm3.429 11.429h9.142V12H7.43zm0 0V20H4v-4.571z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r9-vg5b5h {
  fill: var(--svg-color--d1ff52, #d1ff52);
  d: path("M24 0H0v24h24z");
}

</style>
