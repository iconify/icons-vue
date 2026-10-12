<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uu644c7ob"/><path class="mx5rw7bnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:recipe-book-sharp" /></template>
<style>
.mx5rw7bnl {
  d: path("M9.75 7.25v4.5h4v-4.5m-2 4.5V17m5-9.75V17");
}

.uu644c7ob {
  d: path("M3.75 2.75h16.5v18.5H3.75zm3 0v18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
