<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="eqrn8damu"/><path class="hx-_j2oog"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xpla-background" /></template>
<style>
.eqrn8damu {
  fill: var(--svg-color--00b1ff, #00b1ff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hx-_j2oog {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.824 12.907l-.901.896l6.176 6.181l.901-.901l-6.176-6.182zM4.896 4L4 4.901l6.176 6.176l.896-.896zm14.192.01l-6.165 6.187l.896.896l6.17-6.186zm-8.896 8.907l-6.17 6.187l.895.896l6.176-6.187z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
