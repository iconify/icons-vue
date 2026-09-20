<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c2byu4b5t"/><path clip-rule="evenodd" class="hha60e18i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xdg-background" /></template>
<style>
.c2byu4b5t {
  fill: var(--svg-color--ba9f33, #ba9f33);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hha60e18i {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6 4h7.587c1.918.026 5.785 1.608 5.91 7.727s-3.888 8.065-5.91 8.273H6v-7H4.5v-2.5H6zm2.5 2.5h4.083c1.463.017 4.395 1.09 4.417 5.249c.026 4.923-2.945 5.75-4.417 5.75H8.5V13H13v-2.5H8.5z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
