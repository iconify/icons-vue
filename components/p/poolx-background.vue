<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="acj9wsb7i"/><path class="xgnq1ebhv"/><path class="ah21nwc6i"/><path class="px18b8bda"/><path clip-rule="evenodd" class="q0kww4m6y"/><path class="u65vwsb3b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:poolx-background" /></template>
<style>
.acj9wsb7i {
  fill: var(--svg-color--181b1e, #181b1e);
  d: path("M24 0H0v24h24z");
}

.ah21nwc6i {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.525 10.32l-9.99 2.2L4.3 10.3l.39-.92l4.935 2.1l9.68-2.13l.215.975z");
}

.ft5dv1b6b {
  fill: none;
}

.px18b8bda {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.51 19.31l3.17-14.75l.975.21l-3.165 14.75z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q0kww4m6y {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.91 5L5.08 9.985l1.375 6.085l5.55 2.81l5.62-2.81l1.3-6.07l-3.91-5zm6.59-1H8.415L4 9.75l1.585 7L12 20l6.5-3.25l1.5-7z");
}

.u65vwsb3b {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.61 16.725L8.275 4.9l.785-.62l9.335 11.82l-.785.62z");
}

.xgnq1ebhv {
  fill: var(--svg-color--fff, #fff);
  d: path("m5.85 16.025l9.09-11.75l.79.615l-9.085 11.75l-.79-.615z");
}

</style>
