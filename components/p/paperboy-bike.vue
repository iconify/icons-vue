<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ka3xdfbpz"/><path class="fo3g5heyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:paperboy-bike" /></template>
<style>
.fo3g5heyv {
  d: path("m6 17l3.5-6.5h6L18 17m-8.5-6.5L12 17H6m-3.5-6.5h7m6 0l1-3M2.5 7H7v3.5H2.5Zm7 3.5l2-3.5l5 .5m-4-4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ka3xdfbpz {
  d: path("M2.5 17a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm12 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
