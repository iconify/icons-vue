<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v3of4eb4a"/><path class="gwzceryzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:safety-shield-check" /></template>
<style>
.gwzceryzj {
  d: path("m7.75 12.25l3 3l5.5-5.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v3of4eb4a {
  d: path("M12 2.5c2.5 1.5 5 2 7.5 2v7c0 5-3.5 8.25-7.5 10c-4-1.75-7.5-5-7.5-10v-7c2.5 0 5-.5 7.5-2Z");
}

</style>
