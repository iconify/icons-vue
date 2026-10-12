<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kkead-wrd"/><path class="v4aqohbrc"/><path class="a-h60nb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-recycling-sharp" /></template>
<style>
.a-h60nb3w {
  d: path("M14 12v1.5h-1.5");
}

.kkead-wrd {
  d: path("M8.75 6.25v-3.5h6.5v3.5Zm-6 0h18.5v3.5H2.75zm1.5 3.5h15.5l-1 10v1.5H5.25v-1.5Z");
}

.v4aqohbrc {
  d: path("M14.75 15.5a2.75 2.75 0 1 1-.75-2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
