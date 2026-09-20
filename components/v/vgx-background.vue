<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ga1gk5b5i"/><path class="zvy3epbay"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vgx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ga1gk5b5i {
  fill: var(--svg-color--292375, #292375);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zvy3epbay {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.925 4H4.741a.208.208 0 0 0-.192.288l6.859 15.344c.219.49.923.49 1.141 0l6.902-15.344A.208.208 0 0 0 19.259 4H16.09a.63.63 0 0 0-.57.368l-3.525 7.67l-3.5-7.67A.62.62 0 0 0 7.926 4");
}

</style>
