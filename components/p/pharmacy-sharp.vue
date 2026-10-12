<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ro9_s9bdm"/><path class="ls47ndtwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pharmacy-sharp" /></template>
<style>
.ls47ndtwa {
  d: path("M11.5 8h1.4v3.1H16v1.8h-3.1V16h-1.8v-3.1H8v-1.8h3.1V8z");
}

.ro9_s9bdm {
  d: path("M10.5 3H15v6h6v6h-6v6H9v-6H3V9h6V3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
