<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lfrrrs4_i"/><path class="a-3n09epa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-quality-sharp" /></template>
<style>
.a-3n09epa {
  d: path("m9.01 12.57l2.98 1.86l.51.32l-.51.32l-2.98 1.86l-.51.32v-5zM18.5 3l.3 2.2l2.2.3l-2.2.3l-.3 2.2l-.3-2.2l-2.2-.3l2.2-.3z");
}

.lfrrrs4_i {
  d: path("M2.75 9.25h14.5v11H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
