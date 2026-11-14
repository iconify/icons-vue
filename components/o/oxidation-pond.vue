<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pq5tfebgv"/><path class="dzq9sycvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oxidation-pond" /></template>
<style>
.dzq9sycvg {
  d: path("M6.5 15q1.75-1.75 3.5 0t3.5 0t3.5 0M9 6.5h.01M12 4h.01M15 6.5h.01");
}

.pq5tfebgv {
  d: path("M2.5 15a9.5 5 0 1 0 19 0a9.5 5 0 1 0-19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
