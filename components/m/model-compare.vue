<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="edmdygbre"/><path class="y9sktrb1c"/><path class="jyqytw-sj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:model-compare" /></template>
<style>
.edmdygbre {
  d: path("m7.15 12.38l2.38 1.37q.65.38.65 1.13v2.75q0 .75-.65 1.12l-2.38 1.38q-.65.37-1.3 0l-2.38-1.38q-.65-.37-.65-1.12v-2.75q0-.75.65-1.13l2.38-1.37q.65-.38 1.3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jyqytw-sj {
  d: path("m13.82 14.13l3.68 2.12l3.68-2.12m-3.68 2.12v4.25M6 4.5h12m-1.75-1.75L18 4.5l-1.75 1.75M18 8.5H6m1.75-1.75L6 8.5l1.75 1.75");
}

.y9sktrb1c {
  d: path("m2.82 14.13l3.68 2.12l3.68-2.12M6.5 16.25v4.25m11.65-8.12l2.38 1.37q.65.38.65 1.13v2.75q0 .75-.65 1.12l-2.38 1.38q-.65.37-1.3 0l-2.38-1.38q-.65-.37-.65-1.12v-2.75q0-.75.65-1.13l2.38-1.37q.65-.38 1.3 0");
}

</style>
