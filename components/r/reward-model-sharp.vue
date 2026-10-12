<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="iejo7sb_x"/><path class="pvwrqw3fw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reward-model-sharp" /></template>
<style>
.iejo7sb_x {
  d: path("M2.75 8.75h11.5v12.5H2.75zm3.5 9v-2m2.25 2v-4m2.25 4v-6");
}

.pvwrqw3fw {
  d: path("m16.89 3.12l.99 2.21l.14.32l.35.04l2.41.25l.34.04l-.26.23l-1.8 1.62l-.26.24l.08.34l.5 2.37l.07.34l-.3-.17l-2.1-1.21l-.3-.18l-.3.18l-2.1 1.21l-.3.17l.07-.34l.5-2.37l.08-.34l-.26-.24l-1.8-1.62l-.26-.23l.34-.04l2.41-.25l.35-.04l.14-.32l.99-2.21l.14-.32z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
