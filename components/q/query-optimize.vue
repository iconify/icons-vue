<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v7cg4bv_p"/><path class="t-5siabzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:query-optimize" /></template>
<style>
.t-5siabzh {
  d: path("M7 10.5L4.5 13L7 15.5m3.5-5.5l-1.75 6m3.5-5.5l2.5 2.5l-2.5 2.5M19 14.25l-3.75 4.25H18l-1 3.25l3.75-4.5H18Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7cg4bv_p {
  d: path("M9.8 20.5H2.5v-17h19v10.9m-19-6.65h19");
}

</style>
