<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aiq1-wbzg"/><path class="tib3hgado"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traffic-light-fault" /></template>
<style>
.aiq1-wbzg {
  d: path("M4.5 2h9v20h-9Z");
}

.tib3hgado {
  d: path("M7.5 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm11-4v4m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
