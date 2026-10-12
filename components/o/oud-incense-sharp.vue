<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bf2qhuvnv"/><path class="iijmi-b2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oud-incense-sharp" /></template>
<style>
.bf2qhuvnv {
  d: path("M10 8.5c-1.25-1.25 1.25-2 0-3.25s1.25-2 0-2.5m4 5.75c-1.25-1.25 1.25-2 0-3.25M5.5 10.5h14l-.48.88l-1.79 3.24l-.48.88h-9.5l-.48-.88l-1.79-3.24l-.48-.88zm1 2.5h11");
}

.iijmi-b2l {
  d: path("M11 15.5h3l.4.92l1.7 3.91l.4.92h-9l.4-.92l1.7-3.91l.4-.92z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
