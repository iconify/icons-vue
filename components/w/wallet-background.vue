<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tzn0e5j4g"/><path class="z-plcubla"/><path class="fv-cql7aw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wallet-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fv-cql7aw {
  fill: var(--svg-color--fff, #fff);
  d: path("m14 9.6l-2.4-1.2L6.8 15l3.2 3.4zm.8 2.2V10l2.4 4.4zM9.2 9l.8-3l-3 5z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tzn0e5j4g {
  fill: var(--svg-color--5c02ff, #5c02ff);
  d: path("M24 0H0v24h24z");
}

.z-plcubla {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.2 14.4l-2.4-2.6l-3.6 3V20zm-6.8-3.6L9.2 9L7 11l.8 1.4l2.2-.8zm1.2-2.4V4L14 9.6z");
}

</style>
