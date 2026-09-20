<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGlW42icMZ)" class="r4i437pya"/><path clip-rule="evenodd" class="zu5haabhu"/><path class="o1qbbcuhx"/></g><defs><linearGradient id="SVGlW42icMZ" x1="12" x2="12" y1="4" y2="17.25" gradientUnits="userSpaceOnUse"><stop class="bykak7b6q"/><stop offset=".89" class="f83mxmbxb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mc-background" /></template>
<style>
.bykak7b6q {
  stop-color: var(--svg-color--f4c251, #f4c251);
}

.f83mxmbxb {
  stop-color: var(--svg-color--e47236, #e47236);
}

.ft5dv1b6b {
  fill: none;
}

.o1qbbcuhx {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.226 13.914c.03.05 1.785 3.135 4.65 3.085c.935-.015 1.97-.625 3.125-1.5c1-.89 1.5-2.05 1.5-3.5s-.5-2.61-1.5-3.5c0 0 1.61-1.535 3.5-1.5c1.48.025 3.15.995 4.39 3.665A8.012 8.012 0 0 1 12 19.979a7.964 7.964 0 0 1-7.775-6.065");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.zu5haabhu {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 4c4.41 0 8 3.59 8 8s-3.59 8-8 8s-8-3.59-8-8s3.59-8 8-8m0 11.5c-1-.89-1.5-2.05-1.5-3.5S11 9.39 12 8.5c1 .89 1.5 2.05 1.5 3.5s-.5 2.585-1.5 3.5");
}

</style>
