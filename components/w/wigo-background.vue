<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="s4whj07kn"/><path class="wuljrnbva"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wigo-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s4whj07kn {
  fill: var(--svg-color--070bf0, #070bf0);
  d: path("M24 0H0v24h24z");
}

.wuljrnbva {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 12h-1.714V6.731a13.34 13.34 0 0 1-13.52 3.635L4 10.137L4.457 8.6l.772.229c4.285 1.28 8.971.131 12.034-3.115H12V4h8zM4 12h1.714v5.269a13.34 13.34 0 0 1 13.52-3.635l.766.229l-.457 1.537l-.772-.229a11.87 11.87 0 0 0-12.034 3.115H12V20H4z");
}

</style>
