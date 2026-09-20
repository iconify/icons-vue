<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ouyg_wb2s"/><path clip-rule="evenodd" class="xo4vffbkd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tbtc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ouyg_wb2s {
  fill: var(--svg-color--090502, #090502);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xo4vffbkd {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-1.882 0a6.117 6.117 0 1 1-12.235 0a6.117 6.117 0 0 1 12.235 0M12.94 9.176a.941.941 0 1 1-1.882 0a.941.941 0 0 1 1.882 0m1.882 2.353H9.176v.942h2.353v2.823h.942v-2.823h2.352z");
}

</style>
