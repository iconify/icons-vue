<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t8d4b5b8n"/><path class="d4bc8lb7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-sitting" /></template>
<style>
.d4bc8lb7d {
  d: path("m7 9.5l3-.5l3.5 2M6 12v8.5");
}

.t8d4b5b8n {
  d: path("M8 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 4v5.5h5.5l1.5 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
