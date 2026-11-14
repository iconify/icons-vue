<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wpmm3q26m"/><path class="orua6n77n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:visual-programming" /></template>
<style>
.orua6n77n {
  d: path("m15 12l2.5 2.5L20 12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpmm3q26m {
  d: path("M2.5 2.5h8v7h-8Zm11 12h8v7h-8Zm-3-8.5h5a2 2 0 0 1 2 2v6.5");
}

</style>
