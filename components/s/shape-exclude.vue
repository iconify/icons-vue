<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d3xxo4y6s"/><path class="kyhg65ggd"/><path class="ocmla0jdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shape-exclude" /></template>
<style>
.d3xxo4y6s {
  d: path("M3 3h12v12H3Z");
}

.kyhg65ggd {
  d: path("M9 9h12v12H9Z");
}

.ocmla0jdf {
  d: path("M9 9h6v6H9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
