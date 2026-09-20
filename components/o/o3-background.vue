<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG1QQ7VbeQ)" class="r4i437pya"/><path clip-rule="evenodd" class="x9tmfuors"/></g><defs><linearGradient id="SVG1QQ7VbeQ" x1="12" x2="10.814" y1="6.667" y2="16.901" gradientUnits="userSpaceOnUse"><stop class="trqrzyb4w"/><stop offset="1" class="g3kinpijf"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:o3-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g3kinpijf {
  stop-color: var(--svg-color--06af8f, #06af8f);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.trqrzyb4w {
  stop-color: var(--svg-color--42b06b, #42b06b);
}

.x9tmfuors {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.889 17.333h8.444a2.667 2.667 0 0 0 2.048-4.375a2.445 2.445 0 1 0-3.669-3.23l-.007.013c-.205.293-.356.893.046 1.25c.395.352.976.21 1.286-.077A.668.668 0 1 1 17.541 12l.001.004c-.506 0-1.1.348-1.1 1.107c0 .76.605 1.07 1.1 1.103v.002h.01a.67.67 0 0 1 0 1.34q-.123 0-.224-.004v.004H9.444l.002-.002a3.557 3.557 0 1 1 2.97-1.778c-.3.533-.28.902.091 1.2c.65.325 1.26-.026 1.397-.228a5.334 5.334 0 1 0-5.016 2.567z");
}

</style>
