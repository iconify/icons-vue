<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t6_voobvk"/><path class="wo3c02m2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:visitor-restricted" /></template>
<style>
.t6_voobvk {
  d: path("M10.9 7h6.6v6.6m0 7.8v.1h-11V10.4m4.399-3.453Q11.432 7 12 7c3.5 0 6-1.5 8-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wo3c02m2z {
  d: path("M9.831 13.728L12 18.5l.81-1.783M3.5 3.5l17 17");
}

</style>
