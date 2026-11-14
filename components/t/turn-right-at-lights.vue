<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0vz28bru"/><path class="ht7xlcczt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:turn-right-at-lights" /></template>
<style>
.ht7xlcczt {
  d: path("M18.25 7.25L21 10l-2.75 2.75M3 2.5h6V15H3Zm3 3h.01M6 8.75h.01M6 12h.01");
}

.o0vz28bru {
  d: path("M13 21.5v-8a3.5 3.5 0 0 1 3.5-3.5H21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
