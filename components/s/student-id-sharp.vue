<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uu8i62bpl"/><path class="jzdih3-vd"/><path class="j41dnmbml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:student-id-sharp" /></template>
<style>
.j41dnmbml {
  d: path("M9.75 10.88v2.62L12 15l2.25-1.5v-2.62M8.5 18h7");
}

.jzdih3-vd {
  d: path("m12.45 8.22l3.1 1.56l.45.22l-.45.22l-3.1 1.56L12 12l-.45-.22l-3.1-1.56L8 10l.45-.22l3.1-1.56L12 8z");
}

.uu8i62bpl {
  d: path("M4.75 2.75h14.5v18.5H4.75zm5.5 3h3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
