<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f19y364fg"/><path class="b269h5dzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:undo-all" /></template>
<style>
.b269h5dzp {
  d: path("m11.5 5.5l-4 4l4 4m-4-8l-4 4l4 4");
}

.f19y364fg {
  d: path("M7.5 9.5H15a5 5 0 0 1 0 10h-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
