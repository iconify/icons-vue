<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rh9ghukku"/><path class="sgm4funmc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:monad-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rh9ghukku {
  fill: var(--svg-color--836ef9, #836ef9);
  d: path("M24 0H0v24h24z");
}

.sgm4funmc {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4c-2.31 0-8 5.69-8 8s5.69 8 8 8s8-5.69 8-8s-5.69-8-8-8m-1.247 12.575c-.974-.266-3.593-4.847-3.328-5.822s4.848-3.593 5.822-3.328s3.593 4.847 3.328 5.822s-4.847 3.593-5.822 3.328");
}

</style>
