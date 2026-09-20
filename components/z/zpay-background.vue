<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pndwuj6_y"/><path class="rv-pblgqd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zpay-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pndwuj6_y {
  fill: var(--svg-color--11f, #11f);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rv-pblgqd {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.647 4.941H7.529c-.338 0-.705.269-.705.593v1.638c0 .33.367.593.705.593h4.716L4 15.295h3.967l8.772-7.831c.94-.941.259-2.523-1.092-2.523M8.353 19.06h8.353c.339 0 .47-.268.47-.593v-1.638c0-.329-.131-.593-.47-.593h-4.95L20 8.706h-3.967l-8.772 7.83c-.941.942-.259 2.523 1.092 2.523");
}

</style>
