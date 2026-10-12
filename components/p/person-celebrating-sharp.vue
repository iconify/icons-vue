<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="a7q8jib6e"/><path class="q0dzl5bpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-celebrating-sharp" /></template>
<style>
.a7q8jib6e {
  cx: 12px;
  cy: 7.25px;
  r: 2px;
}

.q0dzl5bpy {
  d: path("M12 12v4.25m-2.5 5l2.5-5l2.5 5M7 5l1.25 5.5L12 12l3.75-1.5L17 5M4.75 13.5l.24 1.76l1.76.24l-1.76.24l-.24 1.76l-.24-1.76l-1.76-.24l1.76-.24zm14.5 0l.24 1.76l1.76.24l-1.76.24l-.24 1.76l-.24-1.76l-1.76-.24l1.76-.24z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
