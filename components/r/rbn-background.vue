<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cmrx9xbee"/><path class="sxyi5l65s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rbn-background" /></template>
<style>
.cmrx9xbee {
  fill: var(--svg-color--e73558, #e73558);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sxyi5l65s {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.003 20a8 8 0 1 0-7.48-5.155l7.6-7.345l4.88 4.715L12.053 17l-.715-.69l4.235-4.095l-3.45-3.335l-7.16 6.92c1.35 2.5 4 4.2 7.04 4.2");
}

</style>
