<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bgvndv3cj"/><path class="thnol90qj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:milestone-post-sharp" /></template>
<style>
.bgvndv3cj {
  d: path("M2.75 2.75h18.5v18.5H2.75zM8 17.5V7");
}

.thnol90qj {
  d: path("M8.5 6.5h7.75l-.33.37l-1.34 1.51l-.33.37l.33.37l1.34 1.51l.33.37H8V6.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
