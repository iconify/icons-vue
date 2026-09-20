<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGBhWe0dIt)" class="r4i437pya"/><path class="jf1py9b8q"/></g><defs><linearGradient id="SVGBhWe0dIt" x1="3.014" x2="18.602" y1="11.703" y2="11.703" gradientUnits="userSpaceOnUse"><stop class="mhtd8-ejt"/><stop offset="1" class="zevovsbbk"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:slnd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jf1py9b8q {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.447 13.815a4.55 4.55 0 0 1-.17-6.488l1.501-1.553a1.176 1.176 0 0 1 1.647-.047c.47.443.485 1.172.042 1.633L6.971 8.913a2.263 2.263 0 0 0 .085 3.232a2.33 2.33 0 0 0 3.265-.085l1.506-1.571a4.775 4.775 0 0 1 6.7-.17a4.643 4.643 0 0 1 .169 6.62l-1.238 1.29a1.176 1.176 0 0 1-1.91-.324a1.14 1.14 0 0 1 .217-1.267l1.242-1.289a2.35 2.35 0 0 0-.09-3.354a2.42 2.42 0 0 0-3.397.084l-1.51 1.572a4.68 4.68 0 0 1-6.563.164m3.42 3.75a1.153 1.153 0 0 1 .899-1.364a8.5 8.5 0 0 0 4.568-3.162a1.176 1.176 0 0 1 1.94.058a1.14 1.14 0 0 1-.039 1.283c-1.91 2.644-4.714 3.806-5.984 4.074a1.167 1.167 0 0 1-1.384-.893zm4.536-9.142a1.155 1.155 0 1 0-.485-2.258c-1.242.263-3.467.997-5.392 3.66a1.14 1.14 0 0 0 .273 1.61a1.176 1.176 0 0 0 1.628-.269c1.487-2.065 3.124-2.564 3.976-2.743");
}

.mhtd8-ejt {
  stop-color: var(--svg-color--ff9050, #ff9050);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.zevovsbbk {
  stop-color: var(--svg-color--fb5e39, #fb5e39);
}

</style>
