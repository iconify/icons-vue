<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ex2nwubem"/><path class="q1-52bg2f"/><path class="jyqytw-sj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:model-compare-sharp" /></template>
<style>
.ex2nwubem {
  d: path("m7.15 12.38l2.38 1.37l.65.38v4.25l-.65.37l-2.38 1.38l-.65.37l-.65-.37l-2.38-1.38l-.65-.37v-4.25l.65-.38l2.38-1.37l.65-.38z");
}

.jyqytw-sj {
  d: path("m13.82 14.13l3.68 2.12l3.68-2.12m-3.68 2.12v4.25M6 4.5h12m-1.75-1.75L18 4.5l-1.75 1.75M18 8.5H6m1.75-1.75L6 8.5l1.75 1.75");
}

.q1-52bg2f {
  d: path("m2.82 14.13l3.68 2.12l3.68-2.12M6.5 16.25v4.25m11.65-8.12l2.38 1.37l.65.38v4.25l-.65.37l-2.38 1.38l-.65.37l-.65-.37l-2.38-1.38l-.65-.37v-4.25l.65-.38l2.38-1.37l.65-.38z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
