<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y86m7phcf"/><path class="d_x824bsi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:strk-background" /></template>
<style>
.d_x824bsi {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 10.316V4l-5.053 9.684H12V20l5.052-9.684z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y86m7phcf {
  fill: var(--svg-color--277fe3, #277fe3);
  d: path("M24 0H0v24h24z");
}

</style>
