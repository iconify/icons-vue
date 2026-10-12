<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="f5itllt7m"/><path class="v5l-mjtro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nursery-rhyme-sharp" /></template>
<style>
.f5itllt7m {
  cx: 8.25px;
  cy: 17.75px;
  r: 3px;
}

.v5l-mjtro {
  d: path("M11.25 17.75v-14c0 2.5 4.5 3 4.5 6.5m1.89 2.57l.75 1.69l.14.32l.35.03l1.84.19l.35.04l-.26.24l-1.38 1.23l-.26.23l.08.35l.38 1.8l.07.34l-.3-.17l-1.6-.92l-.3-.18l-.3.18l-1.6.92l-.3.17l.07-.34l.38-1.8l.08-.35l-.26-.23l-1.38-1.23l-.26-.24l.35-.04l1.84-.19l.35-.03l.14-.32l.75-1.69l.14-.32z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
