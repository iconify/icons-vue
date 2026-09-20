<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h9_cbaclj"/><path clip-rule="evenodd" class="fzavaeggu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:obot-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fzavaeggu {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4 4h6.4v2.667h3.2V4H20v6.4h-2.667v3.2H20V20h-6.4v-2.667h-3.2V20H4v-6.4h2.667v-3.2H4zm3.733 6.4v3.2H10.4v2.667h3.2V13.6h2.667v-3.2H13.6V7.733h-3.2V10.4zM5.6 5.6h3.2v3.2H5.6zm0 9.6h3.2v3.2H5.6zm12.8-9.6h-3.2v3.2h3.2zm-3.2 9.6h3.2v3.2h-3.2z");
}

.h9_cbaclj {
  fill: var(--svg-color--fe0000, #fe0000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
