<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nv_t9blaa"/><path class="m5nf17byo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:professional-certification" /></template>
<style>
.m5nf17byo {
  d: path("m9.5 9.75l1.75 1.75L14.5 8");
}

.nv_t9blaa {
  d: path("m12 2.5l1.553 1.204l1.947-.266l.743 1.819L18.062 6l-.266 1.947L19 9.5l-1.204 1.553l.266 1.947l-1.819.743l-.743 1.819l-1.947-.266L12 16.5l-1.553-1.204l-1.947.266l-.743-1.819L5.938 13l.266-1.947L5 9.5l1.204-1.553L5.938 6l1.819-.743l.743-1.819l1.947.266ZM9 15.75L7.5 21l2.5-1l2 1.5m3-5.75L16.5 21L14 20l-2 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
