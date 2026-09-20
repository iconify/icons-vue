<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="htgvy_brv"/><path clip-rule="evenodd" class="i3h6n0b-k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:paradex-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.htgvy_brv {
  fill: var(--svg-color--04040f, #04040f);
  d: path("M24 0H0v24h24z");
}

.i3h6n0b-k {
  fill: var(--svg-color--cc38ff, #cc38ff);
  fill-rule: evenodd;
  d: path("m16.63 8.599l1.77 2.68h-1.677L15.03 8.713h-2.3V7.375h3.112c.61 0 1.105-.457 1.105-1.02a.97.97 0 0 0-.323-.718c-.2-.185-.476-.3-.782-.3H12.73V4h3.112a2.66 2.66 0 0 1 1.808.69q.195.181.346.397a2.19 2.19 0 0 1 .151 2.288a2.5 2.5 0 0 1-1.518 1.224m-5.763-3.512a2.4 2.4 0 0 0-.346-.397A2.66 2.66 0 0 0 8.713 4H5.6v1.338h3.113c.305 0 .582.114.78.298a.97.97 0 0 1 .325.72c0 .562-.495 1.018-1.105 1.018H5.6v3.906h1.363V8.711h1.75c1.016 0 1.893-.546 2.305-1.338a2.19 2.19 0 0 0-.151-2.287M18.4 12.72h-1.669l-1.558 2.37l-1.558-2.37h-1.668l2.392 3.64L11.947 20h1.668l1.558-2.37L16.731 20h1.67l-2.393-3.64zm-7.202 3.64c0 1.005-.41 1.915-1.073 2.573A3.66 3.66 0 0 1 7.536 20H5.6v-1.34h1.936a2.307 2.307 0 0 0 2.314-2.3c0-.635-.26-1.21-.678-1.626a2.3 2.3 0 0 0-1.636-.674H5.6v-1.34h1.936c2.022 0 3.662 1.63 3.662 3.64");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
