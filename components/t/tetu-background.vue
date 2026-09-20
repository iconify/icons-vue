<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="x5wrk3bao"/><path class="mifh3l30r"/><path class="csebv6z1v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tetu-background" /></template>
<style>
.csebv6z1v {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.995 11.75a4.96 4.96 0 0 1-4.92-4.875C7.19 5.6 6.05 5.6 5.74 5.945l-.07.07A7.45 7.45 0 0 0 4 10.7c0 1.55 1.535 2.55 3.165 2.55h9.67c1.615 0 3.165-.99 3.165-2.55a7.42 7.42 0 0 0-1.74-4.75c-.32-.35-1.46-.35-1.345.925c0 2.595-2.2 4.875-4.92 4.875m.905 7.544l2.4-3.37c.506-.7-.01-1.675-.9-1.675H9.6c-.89 0-1.404.97-.9 1.675l2.4 3.37a1.115 1.115 0 0 0 1.8 0");
}

.ft5dv1b6b {
  fill: none;
}

.mifh3l30r {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 10.25a3 3 0 1 0 0-6.002a3 3 0 0 0 0 6.001");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x5wrk3bao {
  fill: var(--svg-color--04a8f0, #04a8f0);
  d: path("M24 0H0v24h24z");
}

</style>
