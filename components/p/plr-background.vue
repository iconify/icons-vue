<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wb_x2t8ct"/><path class="oqe3u3beu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:plr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oqe3u3beu {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.5 7l-3-3v10h-8v3l3 3v-3h8zm-7-1h-4v4h4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wb_x2t8ct {
  fill: var(--svg-color--00ff24, #00ff24);
  d: path("M24 0H0v24h24z");
}

</style>
