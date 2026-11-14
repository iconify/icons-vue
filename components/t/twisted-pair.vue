<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k-llulbzs"/><path class="bara7tbgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:twisted-pair" /></template>
<style>
.bara7tbgf {
  d: path("M2.5 15C7 15 7 9 12 9s5 6 9.5 6");
}

.k-llulbzs {
  d: path("M2.5 9C7 9 7 15 12 15s5-6 9.5-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
