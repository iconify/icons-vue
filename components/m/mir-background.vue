<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path clip-rule="evenodd" class="til91rbbt"/><path class="no42uyb9s"/><path class="kl1q88uhs"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mir-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.kl1q88uhs {
  fill: var(--svg-color--0061fe, #0061fe);
  d: path("m19.758 8.151l-6.788 3.36v2.02l2.424-1.172v4.225l-2.424 1.188v2.002l6.788-3.58v-1.985l-1.94 1.136v-4.224l1.94-1.019z");
}

.no42uyb9s {
  fill: var(--svg-color--00a3fe, #00a3fe);
  d: path("M4.243 7.424v8.272l1.939.997v-4.899l1.38 3.213l2.014-1.776V18.5l2.909 1.5v-8.406l-2.728-1.28l-1.847 1.411l-1.726-3.283z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.til91rbbt {
  fill: var(--svg-color--01d8dd, #01d8dd);
  fill-rule: evenodd;
  d: path("M4.74 6.582L9.932 4.4c.759-.301 2.604-.725 3.915 0c1.311.726 1.281 1.54 1.103 1.856l4.596 1.02l-1.885 1.006l-4.031-1.006l-1.436.567L15.21 9.5l-2.48 1.346zm4.672-.263l1.784-.735c.224-.08.737-.194 1.001 0c.33.241.144.544-.155.735c-.239.153-.959.48-1.289.625z");
}

</style>
