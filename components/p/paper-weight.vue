<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="obwko8brr"/><path class="bx3757bie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:paper-weight" /></template>
<style>
.bx3757bie {
  d: path("M6.75 18.25a5.25 5.25 0 0 1 10.5 0Z");
}

.obwko8brr {
  d: path("M4 2.5h16v19H4Zm3 4h10M7 10h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
