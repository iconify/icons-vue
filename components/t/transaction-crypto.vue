<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zi_car8rs"/><path class="m8tundb3w"/><path class="ya6zribcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:transaction-crypto" /></template>
<style>
.m8tundb3w {
  d: path("M10.5 3.5h3a8.5 8.5 0 0 1 0 17h-3m-4-11h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ya6zribcw {
  d: path("m12.5 7.5l2 2l-2 2m2 3h-8m2-2l-2 2l2 2");
}

.zi_car8rs {
  d: path("M2 12a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0Z");
}

</style>
