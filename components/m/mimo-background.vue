<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGLqpUvejF)" class="r4i437pya"/><path class="wzp01rb2d"/></g><defs><linearGradient id="SVGLqpUvejF" x1="6.631" x2="12.282" y1="8.81" y2="18.237" gradientUnits="userSpaceOnUse"><stop class="a5_plybwd"/><stop offset="1" class="f231scehu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mimo-background" /></template>
<style>
.a5_plybwd {
  stop-color: var(--svg-color--6df1b5, #6df1b5);
}

.f231scehu {
  stop-color: var(--svg-color--2dd8e0, #2dd8e0);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wzp01rb2d {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.168 7.355h.211c.279 0 .499.143.609.228c.13.097.257.22.371.35c.237.254.49.6.744.972c.296.44.604.942.887 1.437q.396-.675.82-1.331c.253-.38.507-.748.747-1.027c.114-.135.241-.27.372-.38c.106-.08.334-.25.634-.25a.94.94 0 0 1 .49.153c.106.067.207.148.296.232c.173.17.363.389.557.647c.393.51.85 1.22 1.293 2.028c.16.287.317.6.473.916a9.6 9.6 0 0 0 1.428-.38a.66.66 0 0 1 .858.389a.68.68 0 0 1-.389.87c-.397.148-.861.275-1.335.38c.452 1.06.758 2.175.909 3.317a.668.668 0 0 1-1.323.143a11.8 11.8 0 0 0-.93-3.215c-.358.055-.68.098-.929.131l-.16.021a.664.664 0 0 1-.748-.578a.67.67 0 0 1 .57-.756l.14-.018l.532-.071l-.262-.499a15 15 0 0 0-1.179-1.859a7 7 0 0 0-.287-.346a9 9 0 0 0-.646.9a45 45 0 0 0-1.255 2.066l-.089.152a.706.706 0 0 1-1.242-.043A23 23 0 0 0 10 9.667a8 8 0 0 0-.6-.803c-.659.604-1.259 1.525-1.77 2.594c.254.05.473.089.646.114a.667.667 0 0 1 .57.756a.667.667 0 0 1-.747.58a15 15 0 0 1-1.005-.187a18 18 0 0 0-.921 3.363a.67.67 0 0 1-.76.558a.676.676 0 0 1-.554-.769c.198-1.175.506-2.33.92-3.447l-1.33-.33a.676.676 0 0 1 .325-1.305c.397.101.95.24 1.521.371C6.955 9.708 7.85 8.28 9 7.473l.169-.122z");
}

</style>
