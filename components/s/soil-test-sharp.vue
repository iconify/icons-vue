<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hbr_rd1-h"/><path class="u8ccgiy1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soil-test-sharp" /></template>
<style>
.hbr_rd1-h {
  d: path("M9 9.5v8.75a3 3 0 0 0 6 0V9.5");
}

.u8ccgiy1a {
  d: path("M9 16.5h6v1.75a3 3 0 0 1-6 0Zm0 0h6m-3 0v-11m0 1.75c-.25-2.25-1.75-3.75-4.25-4c0 2.5 1.75 4 4.25 4ZM12 6c.25-2.25 1.75-3.25 4.25-3.25C16.25 5 14.5 6 12 6Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
