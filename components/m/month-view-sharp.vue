<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="k06je5b4m"/><path class="etxt20ith"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:month-view-sharp" /></template>
<style>
.etxt20ith {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.38 17.63h.01");
}

.k06je5b4m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25h17.5v17.5H3.25zm0 5h17.5m-8.75 0v12.5M3.25 14.5h17.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
