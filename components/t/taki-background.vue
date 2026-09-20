<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG9WfnpdJL)" class="r4i437pya"/><path class="ntjrocb-l"/></g><defs><linearGradient id="SVG9WfnpdJL" x1="6.77" x2="12.375" y1="5.28" y2="20.5" gradientUnits="userSpaceOnUse"><stop class="kpq8zkb5x"/><stop offset="1" class="xaz_tbb4z"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:taki-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kpq8zkb5x {
  stop-color: var(--svg-color--fdc85b, #fdc85b);
}

.ntjrocb-l {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.365 4.71A1.23 1.23 0 0 1 6.47 4h12.295c.915 0 1.515 1 1.1 1.85l-1.86 3.865c-.2.41-.56.76-1.005.785h-2.165l-2.375 8.575a1.24 1.24 0 0 1-1.185.925h-3.36c-.81 0-1.4-.8-1.19-1.61q.9-3.478 1.96-6.91c.52-1.615 2.18-1.98 3.765-1.98h1.09c-.29-.36-.79-.5-1.49-.5H5.235c-.915 0-1.515-.88-1.1-1.73zm9.47 4.79h1.825a.5.5 0 0 0 .465-.32l1.37-3.5A.498.498 0 0 0 18.03 5H6.805a.5.5 0 0 0-.46.31l-.825 2a.5.5 0 0 0 .46.69h6.07c1.55 0 2.44.785 2.785 1.5m-1.335 1h-1.25c-1.035 0-2.05.3-2.395 1.38c-.6 1.875-1.34 4.785-1.78 6.48c-.08.315.16.64.49.64h2.32c.23 0 .425-.17.485-.385z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xaz_tbb4z {
  stop-color: var(--svg-color--a811aa, #a811aa);
}

</style>
