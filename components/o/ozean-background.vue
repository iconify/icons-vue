<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="l_15nsbmu"/><path class="lvh2qj-it"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ozean-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l_15nsbmu {
  fill: var(--svg-color--0040ff, #0040ff);
  d: path("M0 0h24v24H0z");
}

.lvh2qj-it {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.068 9.57c1.373 0 2.472 1.08 2.472 2.43s-1.099 2.43-2.472 2.43S5.597 13.35 5.597 12s1.098-2.43 2.47-2.43m0 6.43c2.248 0 4.068-1.79 4.068-4s-1.82-4-4.068-4S4 9.79 4 12s1.82 4 4.068 4m5.695-8a.27.27 0 0 0-.271.267v1.066c0 .148.12.267.27.267h4.34a.27.27 0 0 0 .27-.267V8.267a.27.27 0 0 0-.27-.266zm4.881 1.6a.27.27 0 0 0-.271.267v1.068c0 .147.121.266.271.266h1.085c.15 0 .271-.119.271-.266V9.867a.27.27 0 0 0-.271-.267zm-4.881 3.2a.27.27 0 0 0-.271.267v1.066c0 .148.12.267.27.267h1.086a.27.27 0 0 0 .27-.267v-1.066a.27.27 0 0 0-.27-.267zm2.17-1.333c0-.148.12-.267.27-.267h1.085c.15 0 .271.12.271.267v1.067a.27.27 0 0 1-.27.266h-1.086a.27.27 0 0 1-.27-.266zM15.39 14.4a.27.27 0 0 0-.271.267v1.066c0 .147.121.267.27.267h4.34a.27.27 0 0 0 .271-.267v-1.066a.27.27 0 0 0-.271-.267z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
