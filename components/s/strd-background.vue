<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pcvfw6bra"/><path class="v7v_28bvy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:strd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pcvfw6bra {
  fill: var(--svg-color--e91179, #e91179);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v7v_28bvy {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.606 8.885c-.11-1.205-1.28-1.884-2.41-1.884c-.934 0-2.174.515-2.194 1.58c-.035.809.63 1.199 1.3 1.439c.29.1.62.19.98.265l1.364.305q1.176.256 2.075.67c.6.28 1.11.614 1.514 1c.405.37.725.824.94 1.329q.316.751.325 1.69a4.3 4.3 0 0 1-.76 2.534a4.7 4.7 0 0 1-2.16 1.62a9.1 9.1 0 0 1-3.388.564c-2.765 0-6.204-1.36-6.693-4.719l3.749-.67c.1 1.615 1.489 2.39 2.899 2.39c1.104 0 2.33-.525 2.35-1.725c-.01-.71-.35-1.04-1-1.3a8.4 8.4 0 0 0-1.43-.434l-1.66-.385c-1.37-.31-2.45-.805-3.244-1.5A3.54 3.54 0 0 1 5.988 8.84c-.022-.908.255-1.8.79-2.534a5.23 5.23 0 0 1 2.205-1.7a8 8 0 0 1 3.214-.605a6.61 6.61 0 0 1 5.973 3.83z");
}

</style>
