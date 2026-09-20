<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ndg70qblq"/><path clip-rule="evenodd" class="e64v5t_vl"/><path clip-rule="evenodd" class="q1k6d-4ou"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:usdx-background" /></template>
<style>
.e64v5t_vl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.322 7.5C13.902 7.5 16 9.681 16 12.362S13.9 17 11.322 17h-.82v-2h.82c1.478 0 2.68-1.096 2.68-2.638c0-1.543-1.203-2.862-2.68-2.862H6.5V18h-2V7.5z");
}

.ft5dv1b6b {
  fill: none;
}

.ndg70qblq {
  fill: var(--svg-color--fa9b00, #fa9b00);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q1k6d-4ou {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.713 4c4.294 0 7.787 3.588 7.787 8c0 4.411-3.493 8-7.787 8H7.5v-9.5h2V18h2.213c3.203 0 5.787-2.702 5.787-6s-2.584-6-5.787-6H7V4z");
}

</style>
