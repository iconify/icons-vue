<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="moe9itbzo"/><path class="s6dybjb6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wifi-7" /></template>
<style>
.moe9itbzo {
  d: path("M8.25 12.75a4 4 0 0 1 5.5 0m-8.5-3a8 8 0 0 1 11.5 0");
}

.s6dybjb6j {
  d: path("M2.5 7a12 12 0 0 1 17 0M11 15.5h.01m8.74-2.5L16 17.5h3.75l-3 3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
