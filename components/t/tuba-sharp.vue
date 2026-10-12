<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lg1i0imks"/><path class="odq0kwbtm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tuba-sharp" /></template>
<style>
.lg1i0imks {
  d: path("M6.75 3.5v-.75h10.5v.75c-.25 2.5-2.5 4.25-4 5v2h-2.5v-2L7.066 6.658z");
}

.odq0kwbtm {
  d: path("M6 15.75a6 5.25 0 1 0 12 0a6 5.25 0 1 0-12 0m1.76-3.71L4.5 9.5M9 13.25v4m3-4v4m3-4v4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
