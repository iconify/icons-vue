<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jvcchdc4a"/><path class="vseo4cb6c"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ssv-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jvcchdc4a {
  fill: var(--svg-color--009cf2, #009cf2);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vseo4cb6c {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.553 7.218a.34.34 0 0 1 0-.43l2.185-2.664a.338.338 0 0 1 .522 0l2.19 2.665a.34.34 0 0 1 0 .429l-2.19 2.589a.337.337 0 0 1-.522 0L9.55 7.218zm0 10.069a.34.34 0 0 1 0-.43l2.185-2.664a.34.34 0 0 1 .406-.091a.34.34 0 0 1 .116.091l2.19 2.665a.34.34 0 0 1 0 .43l-2.19 2.588a.34.34 0 0 1-.405.092a.34.34 0 0 1-.117-.092L9.55 17.287zM6.396 11.23a.34.34 0 0 1-.004-.43L8.56 8.135a.337.337 0 0 1 .522 0l2.167 2.665a.34.34 0 0 1 0 .43l-2.172 2.588a.337.337 0 0 1-.513 0zm6.356 0a.336.336 0 0 1 0-.43l2.164-2.665a.337.337 0 0 1 .522 0l2.168 2.665a.34.34 0 0 1 0 .43l-2.172 2.588a.337.337 0 0 1-.514 0z");
}

</style>
