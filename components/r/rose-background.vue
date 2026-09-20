<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="yssgnpbmn"/><path class="r97tiud4p"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rose-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r97tiud4p {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.375 7.17a6.31 6.31 0 0 0-4.95-2.53C9.62 4.64 6.84 8.17 6.84 12c0 2.67 1.77 4.665 3.74 4.665q.276.001.545-.05C9.805 15.655 8.96 13.9 8.96 12c0-3.025 2.05-5.385 4.46-5.385c2.635 0 4.465 2.615 4.465 5.385a8.74 8.74 0 0 1-2.025 5.585a6.96 6.96 0 0 1-4.165 2.405s.13.01.305.01a8 8 0 0 0 6.375-12.83M17.16 12c0-2.67-1.77-4.665-3.74-4.665q-.276-.001-.545.05c1.32.96 2.165 2.715 2.165 4.615c0 3.025-2.05 5.385-4.46 5.385c-2.635 0-4.465-2.615-4.465-5.385c.01-2.05.74-4.08 2.025-5.585a6.96 6.96 0 0 1 4.165-2.405S12.175 4 12 4a8 8 0 0 0-6.375 12.83a6.3 6.3 0 0 0 4.95 2.53c3.805 0 6.585-3.53 6.585-7.36");
}

.yssgnpbmn {
  fill: var(--svg-color--0987f4, #0987f4);
  d: path("M24 0H0v24h24z");
}

</style>
