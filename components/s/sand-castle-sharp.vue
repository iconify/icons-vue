<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b7ekwgb7c"/><path class="sevc58tjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sand-castle-sharp" /></template>
<style>
.b7ekwgb7c {
  d: path("M3.6 21h17.15v-7H19v1.5h-1.5V14H15V8.5h-1.25V10H12.6V8.5h-1.2V10h-1.15V8.5H9V14H6.5v1.5H5V14H3.25v7z");
}

.sevc58tjc {
  d: path("M10.75 21v-3.5h2.5V21M12 8.5V5.75m.37-2.86l3.26 1.22l.37.14l-.37.14l-3.26 1.22l-.37.14v-3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
