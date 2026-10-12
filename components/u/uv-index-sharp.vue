<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="zbrf_n9qu"/><path class="v5zuk9hul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:uv-index-sharp" /></template>
<style>
.v5zuk9hul {
  d: path("M12.5 8.25h1.25m-2.49 3.01l.88.88m-3.89.36v1.25m-3.01-2.49l-.88.88M4 8.25H2.75m2.49-3.01l-.88-.88M8.25 4V2.75m3.01 2.49l.88-.88m2.11 16.89v-3.5m3.25 3.5v-6.5m3.25 6.5v-9.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zbrf_n9qu {
  cx: 8.25px;
  cy: 8.25px;
  r: 2.75px;
}

</style>
