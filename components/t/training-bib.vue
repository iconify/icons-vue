<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qpmpv7bvi"/><path class="p85qbul_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:training-bib" /></template>
<style>
.p85qbul_j {
  d: path("M8.75 11.5h6.5v6h-6.5Z");
}

.qpmpv7bvi {
  d: path("M7 2.5V5c0 2-1.25 3.25-2.5 3.75V20A1.5 1.5 0 0 0 6 21.5h12a1.5 1.5 0 0 0 1.5-1.5V8.75C18.25 8.25 17 7 17 5V2.5h-3c0 4.5-4 4.5-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
