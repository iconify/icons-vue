<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="th27cubvw"/><path class="jzcykhbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pinecone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzcykhbjw {
  d: path("M8.75 8.25L12 10.5l3.25-2.25M8.5 13l3.5 2.5l3.5-2.5");
}

.th27cubvw {
  d: path("M12 2.75c3.5 0 6.25 3.5 6.25 7.75c0 5.5-3 10.75-6.25 10.75S5.75 16 5.75 10.5c0-4.25 2.75-7.75 6.25-7.75");
}

</style>
