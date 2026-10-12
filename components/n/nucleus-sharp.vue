<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o7ws7zbmx"/><path class="udyasrbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nucleus-sharp" /></template>
<style>
.o7ws7zbmx {
  d: path("M12 5.65A4.5 4.5 0 0 1 18.35 12a4.5 4.5 0 0 0-5.29-1.06A4.5 4.5 0 0 0 12 5.65Zm0 12.7A4.5 4.5 0 0 1 5.65 12a4.5 4.5 0 0 0 5.29 1.06A4.5 4.5 0 0 0 12 18.35Z");
}

.udyasrbdv {
  d: path("M10.94 13.06a4.5 4.5 0 1 1 2.12-2.12a4.5 4.5 0 1 1-2.12 2.12Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
