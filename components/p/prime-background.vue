<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="b7jr72gej"/><path class="seokt0bnd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:prime-background" /></template>
<style>
.b7jr72gej {
  fill: var(--svg-color--ed1651, #ed1651);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.seokt0bnd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.333 4.889h-2.666v7.777l1.333.667l1.333-.667zm-6.666 4H4l.844 3.795a.45.45 0 0 0 .236.298l1.982.996a.89.89 0 0 1 .494.795v3.005l3.11 1.333v-3.778l-2.488-1.147a.89.89 0 0 1-.494-.622zm6.666 10.222v-3.778l2.49-1.147a.89.89 0 0 0 .493-.622l1.017-4.675H20l-.844 3.795a.45.45 0 0 1-.236.298l-1.982.996a.89.89 0 0 0-.494.795v3.005z");
}

</style>
