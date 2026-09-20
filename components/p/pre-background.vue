<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="a8uxrgb3x"/><path class="urcbwzdok"/><path class="ohax_74gm"/><path class="fimn97f5i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pre-background" /></template>
<style>
.a8uxrgb3x {
  fill: var(--svg-color--2d8eff, #2d8eff);
  d: path("M24 0H0v24h24z");
}

.fimn97f5i {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.5 15H11v2h5.5z");
}

.ft5dv1b6b {
  fill: none;
}

.ohax_74gm {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4.92v14.16c0 .5.42.92.92.92h14.16c.5 0 .92-.42.92-.92V4.92c0-.5-.42-.92-.92-.92H4.92c-.5 0-.92.42-.92.92M17.2 18H6.78c-.5 0-.785-.3-.785-.8V6.78c0-.5.29-.785.785-.785h10.41c.5 0 .805.285.805.785v10.41c0 .5-.3.805-.8.805z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.urcbwzdok {
  fill: var(--svg-color--fff, #fff);
  d: path("M10 14h1.5c1.82.005 3.005-1.83 3-3.5c.01-1.66-1.235-3.51-3-3.5h-4v10H10zm1.265-4.5c.55.04.735.54.735 1c0 .385-.17 1-.68 1H9.995v-2z");
}

</style>
