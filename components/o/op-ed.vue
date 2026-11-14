<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ngnwjpbgj"/><path class="u7l--m7bd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:op-ed" /></template>
<style>
.ngnwjpbgj {
  d: path("M6.25 20.5h12a2 2 0 0 0 2-2v-13a2 2 0 0 0-2-2h-10a2 2 0 0 0-2 2v15a2.5 2.5 0 0 1-2.5-2.5V9h2.5m3-1h2.5m-2.5 4h2.5m-2.5 4h2.5");
}

.u7l--m7bd {
  d: path("M14.5 6.5h3v11h-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
