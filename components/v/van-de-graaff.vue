<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g1-ccoo7u"/><path class="caif28b4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:van-de-graaff" /></template>
<style>
.caif28b4i {
  d: path("M7 13h3v8.5H7Zm-3.5 8.5h10m3-4a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-3-7.5l3 2l-1.5 1.25L18 15");
}

.g1-ccoo7u {
  d: path("M3 7.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
