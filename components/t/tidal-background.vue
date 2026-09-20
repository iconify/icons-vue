<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kch-15bir"/><path class="lbc7r6fjn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tidal-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kch-15bir {
  fill: var(--svg-color--002d95, #002d95);
  d: path("M24 0H0v24h24z");
}

.lbc7r6fjn {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 7.415a5.3 5.3 0 0 1-2.379-.31l-.64-.24a7.38 7.38 0 0 0-5.162 0l-.64.24a5.27 5.27 0 0 1-3.691 0l-.64-.24A7.4 7.4 0 0 0 4 6.407v2.16a5.3 5.3 0 0 1 2.112.33l.64.24a7.38 7.38 0 0 0 5.163 0l.64-.24a5.27 5.27 0 0 1 3.69 0l.64.24A7.3 7.3 0 0 0 20 9.58zM4 15.468h16v2.133H4zm13.621-4.096a5.3 5.3 0 0 0 2.379.31v2.165a7.3 7.3 0 0 1-3.115-.443l-.64-.24a5.27 5.27 0 0 0-3.69 0l-.64.24a7.38 7.38 0 0 1-5.163 0l-.64-.24A5.3 5.3 0 0 0 4 12.834v-2.16c.96-.038 1.93.117 2.848.458l.64.24a5.24 5.24 0 0 0 3.69 0l.64-.24a7.38 7.38 0 0 1 5.163 0z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
