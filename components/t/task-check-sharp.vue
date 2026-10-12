<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ro75teb-w"/><path class="g4gkp79ov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:task-check-sharp" /></template>
<style>
.g4gkp79ov {
  d: path("m4.5 7l1.25 1.25l2-2.25m4.75 1h8.75m-18.5 6.75h6.5v6.5h-6.5zM12.5 17h8.75");
}

.ro75teb-w {
  d: path("M2.75 3.75h6.5v6.5h-6.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
