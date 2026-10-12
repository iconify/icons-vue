<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dfo1y4b4y"/><circle class="o80478h4m"/><path class="j4f4djbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:security-tag-sharp" /></template>
<style>
.dfo1y4b4y {
  d: path("M2.75 9.75h18.5v8.5H2.75zm12.75-6v6");
}

.j4f4djbzt {
  d: path("M6.25 14h4");
}

.o80478h4m {
  cx: 15.5px;
  cy: 14px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
