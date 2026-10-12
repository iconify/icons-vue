<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jdogl9phy"/><path class="h6mi9xbhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sim-card-sharp" /></template>
<style>
.h6mi9xbhw {
  d: path("M8.75 10.75h6.5v7h-6.5zm0 3.5h6.5");
}

.jdogl9phy {
  d: path("M7.75 2.75h6.5l4.5 4.5v14H5.25V2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
