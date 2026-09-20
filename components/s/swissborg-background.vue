<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="u1oo-hb5j"/><path clip-rule="evenodd" class="v0nyk0piw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:swissborg-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u1oo-hb5j {
  fill: var(--svg-color--01c38d, #01c38d);
  d: path("M24 0H0v24h24z");
}

.v0nyk0piw {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("m13.907 4l-1.312.745v6.327l.717.407V6.661l2.46 1.396h.002l.478.27l.4-.225v-.38l-3.34-1.893V5.17l.595-.338l3.459 1.963v1.748l-1.66.937l-.056-.028a.7.7 0 0 0-.311-.075a.72.72 0 0 0-.717.726c0 .4.322.726.717.726c.366 0 .67-.28.708-.652l.007-.063l1.675-.945l1.554.882v3.903l-1.555.882l-6.323-3.59v-6.5L10.092 4L5.918 6.37v2.163L4 9.62v4.754l1.918 1.09v2.166L10.092 20l1.313-.745v-6.34l-.717-.408v4.833l-2.94-1.667l-.4.225v.38l3.34 1.894v.658l-.596.338l-3.458-1.963v-1.748l1.66-.937l.056.028q.153.075.311.075a.72.72 0 0 0 .717-.726c0-.4-.322-.726-.717-.726c-.366 0-.67.28-.709.652l-.006.063l-1.675.946l-1.554-.883v-3.903l1.555-.882l6.323 3.59v6.5l1.312.746l4.175-2.37v-2.163L20 14.38V9.626l-1.918-1.089V6.37zM6.634 6.795l3.458-1.963l.596.338v.658L6.634 8.127zm.372 1.953l3.682-2.088v4.179zm6.306 4.413l3.682 2.091l-3.682 2.088zm0 5.669v-.658l4.054-2.299v1.332l-3.459 1.963z");
}

</style>
