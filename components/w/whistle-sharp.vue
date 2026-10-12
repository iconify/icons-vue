<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r3a1m2bje"/><circle class="hyej5rbam"/><path class="lvvh3abpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whistle-sharp" /></template>
<style>
.hyej5rbam {
  cx: 9.25px;
  cy: 14.25px;
  r: 2.25px;
}

.lvvh3abpj {
  d: path("M13.5 5.25L14.75 3m2.5 2.5L18 3.25");
}

.r3a1m2bje {
  d: path("M9.25 8h12v5h-5.88a6.25 6.25 0 1 1-6.12-5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
