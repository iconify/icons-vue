<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o80jtlb-t"/><path class="mfr5q0fqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sitemap-sharp" /></template>
<style>
.mfr5q0fqz {
  d: path("M10 15.75h4v5.5h-4zm7.25 0h4v5.5h-4z");
}

.o80jtlb-t {
  d: path("M8.75 2.75h6.5V8h-6.5zM12 8v8m-7.25-.25v-4h14.5v4m-16.5 0h4v5.5h-4z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
