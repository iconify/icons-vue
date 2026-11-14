<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_vcnnbnq"/><path class="icxb1ibvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phishing-email" /></template>
<style>
.d_vcnnbnq {
  d: path("M4.5 4h13a2 2 0 0 1 2 2v5.5H14l-3 5v.5H4.5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2Z");
}

.icxb1ibvm {
  d: path("m6 7.5l5 3.5l5-3.5m3.5 7V19a2.25 2.25 0 0 1-4.5 0v-1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
