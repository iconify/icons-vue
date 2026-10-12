<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tsah-tbjq"/><path class="fycpqq3xc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:task-sharp" /></template>
<style>
.fycpqq3xc {
  d: path("m8.5 11.25l3 3L20.25 5");
}

.tsah-tbjq {
  d: path("M20.25 12v8.25H3.75V3.75H14.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
