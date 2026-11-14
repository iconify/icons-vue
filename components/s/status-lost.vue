<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ci-6j0b9t"/><path class="fqostxb6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:status-lost" /></template>
<style>
.ci-6j0b9t {
  d: path("M2.5 3h19v4.5h-19ZM4 7.5h16v14H4Z");
}

.fqostxb6q {
  d: path("M10 12.25a2 2 0 1 1 3.5 1.5l-1.5 1v.5m0 3.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
