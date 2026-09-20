<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uhvnijbjh"/><path class="t27ty8ewl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tomi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t27ty8ewl {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.626 4.09c-2.882.535-5.289 2.786-6.176 5.794a7.1 7.1 0 0 0-.21 2.159c.02 1.64.365 2.964 1.097 4.158l.437.723l4.774-2.989V20h2.912v-5.982l4.822 2.712s1.213-2.038 1.116-2.12a304 304 0 0 0-3.726-2.3l-3.668-2.261l-2.48 1.538a31 31 0 0 1-2.634 1.538c-.116 0-.14-.306-.102-1.242c.039-1.068.102-1.359.442-2.101a5.19 5.19 0 0 1 8.816-1.223a6.05 6.05 0 0 1 1.135 2.528c.073.374.145.694.16.704l1.208.742l1.174.718l.039-1.048c.053-1.436-.146-2.377-.781-3.726a7.1 7.1 0 0 0-2.615-3.105A8.14 8.14 0 0 0 10.63 4.09z");
}

.uhvnijbjh {
  fill: var(--svg-color--ff0083, #ff0083);
  d: path("M24 0H0v24h24z");
}

</style>
