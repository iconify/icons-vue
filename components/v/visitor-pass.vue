<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ocgfisbid"/><path class="kk680c1tx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:visitor-pass" /></template>
<style>
.kk680c1tx {
  d: path("m9.5 13l2.5 5.5l2.5-5.5");
}

.ocgfisbid {
  d: path("M6.5 7h11v14.5h-11Zm4 2.75h3M4 2.5C6 5.5 8.5 7 12 7s6-1.5 8-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
