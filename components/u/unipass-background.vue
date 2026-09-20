<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xb8k72bvc"/><path clip-rule="evenodd" class="z1-j00blg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:unipass-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xb8k72bvc {
  fill: var(--svg-color--42eab2, #42eab2);
  d: path("M24 0H0v24h24z");
}

.z1-j00blg {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M16.017 6.921a.52.52 0 0 0-.156-.368a.54.54 0 0 0-.377-.153h-2.932a.54.54 0 0 0-.378.153a.52.52 0 0 0-.156.368v2.755c0 .138.056.27.156.368a.54.54 0 0 0 .378.153h2.9a.5.5 0 0 1 .376.155a.46.46 0 0 1 .115.383c-.33 1.585-1.69 2.815-3.392 3.03a.6.6 0 0 0-.373.18a.57.57 0 0 0-.16.374v2.755a.5.5 0 0 0 .155.365a.5.5 0 0 0 .379.14c3.987-.25 7.177-3.272 7.447-7.055a.48.48 0 0 0-.14-.37a.5.5 0 0 0-.375-.151h-2.933a.54.54 0 0 1-.377-.153a.52.52 0 0 1-.157-.369zM8 17.079c0 .138-.056.27-.156.368a.54.54 0 0 1-.377.153H4.533a.54.54 0 0 1-.377-.153a.52.52 0 0 1-.156-.368v-2.755c0-.138.056-.27.156-.368a.54.54 0 0 1 .377-.152h2.9a.5.5 0 0 0 .38-.158a.46.46 0 0 0 .113-.387a3.85 3.85 0 0 0-1.2-2.045a4 4 0 0 0-2.194-.984a.6.6 0 0 1-.372-.18a.57.57 0 0 1-.16-.374V6.921a.5.5 0 0 1 .155-.365a.5.5 0 0 1 .379-.139c3.987.25 7.175 3.272 7.448 7.055a.48.48 0 0 1-.142.37a.5.5 0 0 1-.373.151H8.534a.54.54 0 0 0-.378.152a.52.52 0 0 0-.156.368z");
}

</style>
