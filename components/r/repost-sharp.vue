<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="jucztbchv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:repost-sharp" /></template>
<style>
.jucztbchv {
  d: path("M7.25 12V9.75h9m-1.75-2l1.75 2l-1.75 2m2.25.25v2.25h-9m1.75 2l-1.75-2l1.75-2");
}

.pw7p-85ys {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
