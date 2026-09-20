<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gwhctpb9o"/><path class="o5b4c5uew"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xeta-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gwhctpb9o {
  fill: var(--svg-color--ff31ff, #ff31ff);
  d: path("M24 0H0v24h24z");
}

.o5b4c5uew {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.333 6.667a1.333 1.333 0 1 0 0-2.667a1.333 1.333 0 0 0 0 2.667m13.334 0a1.333 1.333 0 1 0 0-2.667a1.333 1.333 0 0 0 0 2.667m0 12.8a1.333 1.333 0 1 0 0-2.667a1.333 1.333 0 0 0 0 2.667M5.333 20a1.333 1.333 0 1 0 0-2.667a1.333 1.333 0 0 0 0 2.667m10.859-2.667a1.13 1.13 0 0 1-.95-.507a1.2 1.2 0 0 1-.16-.346a3.2 3.2 0 0 0-6.17 0a1.17 1.17 0 0 1-.405.613c-.198.16-.443.24-.694.24h-.005a1.14 1.14 0 0 1-1.141-1.142a1.13 1.13 0 0 1 .506-.949q.162-.105.347-.16a3.205 3.205 0 0 0 0-6.17a1.17 1.17 0 0 1-.613-.406a1.13 1.13 0 0 1-.24-.693v-.006a1.141 1.141 0 0 1 2.09-.634c.07.106.123.224.16.346a3.205 3.205 0 0 0 6.171 0c.066-.242.208-.457.405-.613c.198-.16.443-.24.694-.24h.005a1.141 1.141 0 0 1 .635 2.09q-.162.105-.347.16a3.2 3.2 0 0 0 0 6.171c.243.066.458.208.613.406c.16.197.24.442.24.693v.005a1.143 1.143 0 0 1-1.14 1.142m-4.192-4a1.333 1.333 0 1 0 0-2.667a1.333 1.333 0 0 0 0 2.667");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
