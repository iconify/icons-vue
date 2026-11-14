<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o-v__ubif"/><path class="i7r1u8eqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-tag-stack" /></template>
<style>
.i7r1u8eqd {
  d: path("m9.5 5.25l2-2.75H20A1.5 1.5 0 0 1 21.5 4v11a1.5 1.5 0 0 1-1.5 1.5m-12.75-2h.01");
}

.o-v__ubif {
  d: path("M7.5 7.5h10v14h-10l-5-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
