<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nlgw6m5fw"/><path class="cd4vdvhjj"/><path class="eiwx3vrwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tumour-marker" /></template>
<style>
.cd4vdvhjj {
  fill: currentColor;
  d: path("M10.869 18.052A3.48 3.48 0 0 1 8.5 19C6.6 19 5 17.4 5 15.5V11h7v4.5c0 .427-.081.838-.227 1.22");
}

.eiwx3vrwj {
  d: path("M16.75 14.5h4.75v7h-4.75l-2.5-3.5Zm.5 3.5h.01");
}

.nlgw6m5fw {
  d: path("M5 2.5v13C5 17.4 6.6 19 8.5 19a3.48 3.48 0 0 0 2.378-.956m.899-1.335c.144-.379.223-.786.223-1.209v-13m-8.5 0h10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
