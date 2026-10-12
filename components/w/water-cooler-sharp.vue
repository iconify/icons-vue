<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x1hlo6bov"/><path class="gxrhmbc_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-cooler-sharp" /></template>
<style>
.gxrhmbc_t {
  d: path("M8.75 18.25V14h6.5v4.25ZM10.5 14v1.25m3-1.25v1.25");
}

.x1hlo6bov {
  d: path("M10.75 11.25V9.522L9.35 8.9l-2.1-.933V2.75h9.5v5.217l-2.1.933l-1.4.622v1.728Zm-5 0h12.5v10H5.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
