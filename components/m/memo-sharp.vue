<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qb0m1ebnx"/><path class="psfa55xxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:memo-sharp" /></template>
<style>
.psfa55xxl {
  d: path("M14.5 21v-5h5M7.25 5.75h9.5v3h-9.5zm0 6.25h9.5m-9.5 3.25h4.5");
}

.qb0m1ebnx {
  d: path("M5.75 2.75h14V16l-5.25 5.25H4.25V2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
