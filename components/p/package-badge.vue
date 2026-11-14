<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g8f0hjy3o"/><path class="sktsamlkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:package-badge" /></template>
<style>
.g8f0hjy3o {
  d: path("M13.063 18.968L11 20l-8.5-4.25v-9L11 2.5l8.5 4.25v4.497");
}

.sktsamlkk {
  d: path("M2.5 6.75L11 11l8.5-4.25M11 11v3.1m0 2.9v3m6.75-6l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
