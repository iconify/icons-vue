<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jdtbizblc"/><path class="wpqqv-bxp"/><path class="fpp_y6h7b"/><path class="qmnl6kbeo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wnk-background" /></template>
<style>
.fpp_y6h7b {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.563 16.979c-.556-.32-1.252-.142-1.798.193a2.97 2.97 0 0 1-1.558.437a2.843 2.843 0 0 1-2.899-2.786a2.84 2.84 0 0 1 2.9-2.786a2.96 2.96 0 0 1 1.566.443c.58.362 1.341.54 1.901.155c.551-.377.697-1.148.198-1.6a5.47 5.47 0 0 0-3.67-1.388c-2.96 0-5.375 2.315-5.375 5.176S9.238 20 12.208 20a5.46 5.46 0 0 0 3.623-1.355c.541-.471.353-1.304-.268-1.666");
}

.ft5dv1b6b {
  fill: none;
}

.jdtbizblc {
  fill: var(--svg-color--e5b909, #e5b909);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qmnl6kbeo {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.299 7.624c.315-.301.315-.79-.024-1.068A11.57 11.57 0 0 0 11.957 4a11.58 11.58 0 0 0-7.223 2.48a.7.7 0 0 0-.038 1.069c.32.31.847.315 1.205.042a9.87 9.87 0 0 1 6.056-2.043c2.34 0 4.48.791 6.137 2.104c.353.282.88.282 1.2-.028zm-2.024 1.934c.32-.301.32-.786-.023-1.054a8.58 8.58 0 0 0-5.29-1.793c-1.976 0-3.798.65-5.219 1.736c-.348.264-.353.753-.042 1.055c.32.315.847.315 1.214.047a6.88 6.88 0 0 1 4.047-1.29c1.548 0 2.974.499 4.1 1.337c.366.268.893.273 1.218-.038zm-2.301 2.518c.31-.302.315-.782-.038-1.03a5.16 5.16 0 0 0-2.979-.928c-1.096 0-2.108.33-2.931.894c-.358.25-.358.73-.047 1.03c.32.316.856.307 1.256.076a3.46 3.46 0 0 1 3.478.019c.395.235.932.25 1.256-.061z");
}

.wpqqv-bxp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.005 16.236a1.412 1.412 0 1 0 0-2.823a1.412 1.412 0 0 0 0 2.823");
}

</style>
