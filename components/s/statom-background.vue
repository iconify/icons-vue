<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pcvfw6bra"/><path class="nffql6zni"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:statom-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nffql6zni {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.701 8.15l-2.81.975a.34.34 0 0 1-.42-.205A2.91 2.91 0 0 0 11.846 7c-1.19 0-2.235.66-2.235 1.505c0 1.305 2.515 1.81 3.775 1.9c4.23.595 5.165 3.22 5.105 4.455c.115 1.715-.925 5.14-6.045 5.14c-4.85 0-6.6-2.97-6.94-4.69a.31.31 0 0 1 .225-.355l2.84-.78c.18-.05.365.075.41.265c.5 2.17 2.505 2.56 3.465 2.56c.825 0 2.475-.4 2.475-1.725c0-1.67-2.895-1.69-5.51-2.475c-2.61-.785-3.375-2.55-3.375-4.035c0-1.48.535-4.765 5.815-4.765c3.95 0 5.62 2.36 6.05 3.77c.05.16-.04.325-.195.38z");
}

.pcvfw6bra {
  fill: var(--svg-color--e91179, #e91179);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
