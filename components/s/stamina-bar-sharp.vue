<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r-4bww97h"/><path class="b9yec0b3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stamina-bar-sharp" /></template>
<style>
.b9yec0b3d {
  d: path("M13.25 10.75h5.5v2.5h-5.5z");
}

.r-4bww97h {
  d: path("m6.22 9.28l-2.94 2.94l-.28.28h2.5l-.15.37l-.7 1.76l-.15.37l.26-.3l2.73-3.15l.26-.3h-2.5l.19-.35l.87-1.55L6.5 9zm4.53-1.03h10.5v7.5h-10.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
