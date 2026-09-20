<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bdjp02nsb"/><path clip-rule="evenodd" class="oyl2hgbou"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:props-background" /></template>
<style>
.bdjp02nsb {
  fill: var(--svg-color--24d2fd, #24d2fd);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.oyl2hgbou {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.5 8.5h5V4.144C12.935 4.017 12.603 4 12 4a8 8 0 0 0-8 8c0 3.118 1.898 5.817 4.5 7.137zm7-3.637V15.5h-5v4.305c.565.126.897.195 1.5.195a8 8 0 0 0 8-8c0-3.118-1.898-5.817-4.5-7.137m-2 8.637h-3v-3h3z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
