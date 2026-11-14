<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v7jjuqfnq"/><path class="jtegwwo-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wheelchair" /></template>
<style>
.jtegwwo-n {
  d: path("M14.505 12.345a5.5 5.5 0 1 1-9.01 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7jjuqfnq {
  d: path("M8 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM10 8v4.5h5.5l2.5 7");
}

</style>
