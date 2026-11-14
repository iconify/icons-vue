<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d0ziisbwr"/><path class="mjpq51byo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medical-history" /></template>
<style>
.d0ziisbwr {
  d: path("M4.75 2.5H19.5v19H4.75Zm3.5 0v19");
}

.mjpq51byo {
  d: path("M10.25 12h1.5l1-2.5l1.75 5l1-2.5H17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
