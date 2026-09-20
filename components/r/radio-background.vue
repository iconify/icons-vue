<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="k1-btabrq"/><path clip-rule="evenodd" class="wko1iacki"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:radio-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k1-btabrq {
  fill: var(--svg-color--ec1d25, #ec1d25);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wko1iacki {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.588 12c0 3.59-2.997 6.588-6.588 6.588c-1.76 0-3.384-.72-4.574-1.882h1.75v-2.824h1.21l2.15 2.824h2.692l-2.287-2.824c1.177-.235 2.353-1.647 2.353-3.294c0-2.353-2.216-3.294-3.294-3.294H7.426A6.56 6.56 0 0 1 12 5.412c3.59 0 6.588 2.997 6.588 6.588M6.824 7.962A6.54 6.54 0 0 0 5.412 12c0 1.506.532 2.918 1.412 4.038zM20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-8.47 0H9.175V9.176h2.353c.706 0 1.412.368 1.412 1.412S12.235 12 11.53 12");
}

</style>
