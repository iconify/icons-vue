<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="i8k0c1tsi"/><path class="l9jvunbeu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:spa-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i8k0c1tsi {
  fill: var(--svg-color--4fd6cf, #4fd6cf);
  d: path("M24 0H0v24h24z");
}

.l9jvunbeu {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.566 13.142a3.426 3.426 0 0 1 .017 6.851h-.017a3.425 3.425 0 0 1-3.426-3.425c0-.092 0-.177.012-.263c.006-.16.017-.314 0-.48a5.73 5.73 0 0 0-5.019-4.961c-.17-.017-.325-.011-.49-.011l-.212.005a3.425 3.425 0 1 1-.011-6.85h.011a3.426 3.426 0 0 1 3.414 3.705c-.005.177-.011.354.012.542a5.77 5.77 0 0 0 5.138 4.887c.131.011.257.006.383 0zm.057-2.284a3.426 3.426 0 1 0-.114-6.85a3.426 3.426 0 0 0 .114 6.85m-9.192 2.284a3.425 3.425 0 1 1 0 6.85a3.425 3.425 0 0 1 0-6.85");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
