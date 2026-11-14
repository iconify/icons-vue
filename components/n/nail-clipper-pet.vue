<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y1fiz1f-s"/><path class="jnv3fzi8f"/><path class="nucholk3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nail-clipper-pet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnv3fzi8f {
  d: path("M20.5 7Q18 10.5 13 10.5l-10 4");
}

.nucholk3q {
  d: path("M11.25 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4.5 9.5a2.5 1.5 0 1 0 5 0a2.5 1.5 0 1 0-5 0m-.25-3.75h.01M18.25 15h.01M21 16.25h.01");
}

.y1fiz1f-s {
  d: path("M16.5 3.5q-3.5 2-3.5 7L9.5 21");
}

</style>
