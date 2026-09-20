<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lvcjnlbee"/><path class="vn--t0jqy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mars4-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lvcjnlbee {
  fill: var(--svg-color--cf2437, #cf2437);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vn--t0jqy {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.37 4l-5.015 8.75a2.43 2.43 0 0 0-.32 1.311c.026 1.172.785 2.327 2.075 2.327h8.76V20h3.096v-4.644a2.064 2.064 0 0 0-2.064-2.064H8.58l5.366-9.287h-3.575z");
}

</style>
