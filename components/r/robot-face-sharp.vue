<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wtrnw5zoe"/><path class="mg_q2s1ic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:robot-face-sharp" /></template>
<style>
.mg_q2s1ic {
  d: path("M7 8.75h3.25v3H7zm6.75 0H17v3h-3.25zM8 14.25h8V17H8zm2.75 0V17m2.5-2.75V17");
}

.wtrnw5zoe {
  d: path("M3.25 4.25h17.5v15.5H3.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
