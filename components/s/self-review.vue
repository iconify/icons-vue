<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e1rz5sb8w"/><path class="gt9e_ob3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:self-review" /></template>
<style>
.e1rz5sb8w {
  d: path("M5.75 8.75a6.25 6.75 0 1 0 12.5 0a6.25 6.75 0 1 0-12.5 0Z");
}

.gt9e_ob3n {
  d: path("M10.75 15.5h2.5v6h-2.5ZM12 5.5l.882 2.036l2.209.21l-1.664 1.468l.483 2.165L12 10.25l-1.91 1.129l.483-2.165l-1.664-1.468l2.209-.21Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
