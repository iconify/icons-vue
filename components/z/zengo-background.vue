<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="i0245tpjh"/><path class="vgxtqm8dg"/><path class="c-zoqubio"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zengo-background" /></template>
<style>
.c-zoqubio {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.128 9.421c.24-.304-.048-.865-.449-.865H9.09L7.744 10.27h4.469l-3.364 4.31c-.272.352-.064.865.433.865h5.622l1.345-1.714h-4.485z");
}

.ft5dv1b6b {
  fill: none;
}

.i0245tpjh {
  fill: var(--svg-color--ea9c2f, #ea9c2f);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vgxtqm8dg {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.746 5.128H11.78l-1.345 1.714h5.798c1.49 0 2.066 1.282 1.506 2.083c-.32.448-2.403 3.075-2.403 3.075h2.259s.656-.849 1.345-1.73c.593-.753 1.586-2.114.72-3.556c-.928-1.586-2.258-1.586-2.914-1.586M6.254 15.075C6.574 14.627 8.657 12 8.657 12H6.398s-.656.849-1.345 1.73c-.593.753-1.57 2.114-.72 3.556c.928 1.585 2.274 1.585 2.914 1.585h4.966l1.345-1.73H7.76c-1.474 0-2.066-1.28-1.506-2.066");
}

</style>
