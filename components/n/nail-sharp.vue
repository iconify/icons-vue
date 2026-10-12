<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ylsgy9bpa"/><path class="gxjbc7bsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nail-sharp" /></template>
<style>
.gxjbc7bsd {
  d: path("m13.83 9.15l1.02 1.02l.53.53l-.53.53l-6.57 6.56l-.53.53l-.66.36l-3.18 1.71l-.66.36l.36-.66l1.71-3.18l.36-.66l.53-.53l6.56-6.57l.53-.53z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ylsgy9bpa {
  d: path("m12.97 4.13l6.9 6.9l.88.88l-.88.88l-.32.32l-.88.88l-.88-.88l-6.9-6.9l-.88-.88l.88-.88l.32-.32l.88-.88z");
}

</style>
