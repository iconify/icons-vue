<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xqcr9k9bj"/><path class="nk204w2hx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wizard-hat-sharp" /></template>
<style>
.nk204w2hx {
  d: path("m12.75 10.22l.41.89l.15.32l.34.04l.98.12l.35.04l-.26.24l-.72.66l-.26.24l.07.34l.19.97l.07.34l-.31-.17l-.85-.48l-.31-.17l-.31.17l-.85.48l-.31.17l.07-.34l.19-.97l.07-.34l-.26-.24l-.72-.66l-.26-.24l.35-.04l.98-.12l.34-.04l.15-.32l.41-.89l.15-.32z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xqcr9k9bj {
  d: path("m14.07 3.91l3.36 11.93l.32 1.16H6.25l.56-1.06l6.38-12.13l.56-1.06zM2.75 17h18.5v3.5H2.75z");
}

</style>
