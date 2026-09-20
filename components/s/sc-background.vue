<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="heu1i0mzt"/><path clip-rule="evenodd" class="qdjrwtkyv"/><path class="dgcr__brr"/><path class="l500b-bff"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sc-background" /></template>
<style>
.dgcr__brr {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4.5a7.5 7.5 0 1 0 0 15a7.5 7.5 0 0 0 0-15M4 12a8 8 0 0 1 8-8a8 8 0 1 1-8 8");
}

.ft5dv1b6b {
  fill: none;
}

.heu1i0mzt {
  fill: var(--svg-color--15d47b, #15d47b);
  d: path("M24 0H0v24h24z");
}

.l500b-bff {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.75 8a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qdjrwtkyv {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.5 14.5V12a2.5 2.5 0 1 0-2.5 2.5zm-2.5-7a4.5 4.5 0 1 0 0 9h4a.5.5 0 0 0 .5-.5v-4A4.5 4.5 0 0 0 12 7.5");
}

</style>
