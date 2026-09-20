<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vy3xu6xon"/><path class="as7cgr0lw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:velas-background" /></template>
<style>
.as7cgr0lw {
  fill: var(--svg-color--fff, #fff);
  d: path("m15 10.2l-2.996 5.4L9 10.2zm3-1.8L6 8.396L12.004 19.2zM4 4.8l1 1.804h14L20 4.8z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vy3xu6xon {
  fill: var(--svg-color--0137c1, #0137c1);
  d: path("M24 0H0v24h24z");
}

</style>
