<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG0lyYIbup)" class="r4i437pya"/><path class="jj8gev0il"/></g><defs><linearGradient id="SVG0lyYIbup" x1="6.731" x2="17.352" y1="5.694" y2="17.59" gradientUnits="userSpaceOnUse"><stop class="f1fzxhz7x"/><stop offset=".25" class="cskv3jb6d"/><stop offset=".51" class="v62blwbvo"/><stop offset=".73" class="fv6p7cbxf"/><stop offset="1" class="ixan_qb9t"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:topia-background" /></template>
<style>
.cskv3jb6d {
  stop-color: var(--svg-color--d9fe35, #d9fe35);
}

.f1fzxhz7x {
  stop-color: var(--svg-color--ffa708, #ffa708);
}

.ft5dv1b6b {
  fill: none;
}

.fv6p7cbxf {
  stop-color: var(--svg-color--e4b685, #e4b685);
}

.ixan_qb9t {
  stop-color: var(--svg-color--f66aff, #f66aff);
}

.jj8gev0il {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.533 4H10.4v5.333h3.2V4h5.867v16H13.6v-5.333h-3.2V20H4.533z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.v62blwbvo {
  stop-color: var(--svg-color--9cfdde, #9cfdde);
}

</style>
