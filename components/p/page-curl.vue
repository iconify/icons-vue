<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ix7bgnnlg"/><path class="n740cbb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:page-curl" /></template>
<style>
.ix7bgnnlg {
  d: path("M6 2.5h12a2 2 0 0 1 2 2V13l-8 8.5H6a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2Z");
}

.n740cbb0b {
  d: path("M20 13q-8 0-8 8.5M7.5 7h9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
