<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tv9hpcfju"/><path class="ptecjnn7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:verdict-paper-sharp" /></template>
<style>
.ptecjnn7n {
  d: path("m18.34 14.4l1.06-1.06l.53-.53l-.53-.53l-3.18-3.18l-.53-.53l-.53.53l-1.06 1.06l-.53.53l.53.53l3.18 3.18l.53.53zm-.14-4.1l2.55-2.55");
}

.tv9hpcfju {
  d: path("M2.75 2.75h12.5v18.5H2.75zM6 7h6m-6 3.25h4m-4 7.5h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
