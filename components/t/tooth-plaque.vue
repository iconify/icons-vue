<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q267_qb7f"/><path class="n-1y55boq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-plaque" /></template>
<style>
.n-1y55boq {
  d: path("M4.75 12q1.75-2.5 3.5 0Q10 9.5 12 12q2-2.5 3.75 0q1.75-2.5 3.5 0");
}

.q267_qb7f {
  d: path("M8 3C5 3 4 5 4 8s1.5 5 2.5 7l1 5c.25 1.25 1.75 1.25 2 0l1-4.5c.25-1 2.75-1 3 0l1 4.5c.25 1.25 1.75 1.25 2 0l1-5c1-2 2.5-4 2.5-7s-1-5-4-5c-1.5 0-2.5 1-4 1S9.5 3 8 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
