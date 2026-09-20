<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="x9mecyf4c"/><path class="ex5jpo_it"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nex-background" /></template>
<style>
.ex5jpo_it {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.588 17.755l4.235 1.102v-8.443c0-.593.424-1.402 1.195-1.35c.777.056 1.158.607 1.158 1.105v8.974l4.235.857V7.026C17.444 4.546 16.207 4 15.247 4C12 4 11.42 7.106 11.379 8.536h-.556V5.351L6.588 6.574z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x9mecyf4c {
  fill: var(--svg-color--fff600, #fff600);
  d: path("M24 0H0v24h24z");
}

</style>
