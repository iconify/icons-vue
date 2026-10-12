<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mteqj5btx"/><circle class="d4da7x21x"/><path class="mljaf99ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:post-scheduled-sharp" /></template>
<style>
.d4da7x21x {
  cx: 16.75px;
  cy: 16.75px;
  r: 4.5px;
}

.mljaf99ue {
  d: path("M16.75 14.75v2L18 18");
}

.mteqj5btx {
  d: path("M2.75 2.75h14.5v14.5H2.75zm3.75 4.5h7m-7 3.5h4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
