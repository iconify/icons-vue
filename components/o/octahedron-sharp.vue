<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tn8wl4wgg"/><path class="d6qn0tbqp"/><path class="n3q3-os0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:octahedron-sharp" /></template>
<style>
.d6qn0tbqp {
  d: path("m12 4l-.5 9l.5 7");
}

.n3q3-os0w {
  d: path("m6.25 12.05l5.25.95l6.5-1.15");
}

.tn8wl4wgg {
  d: path("m12.87 3.4l7.01 7.2l.87.9l-.82.94l-7.11 8.12l-.82.94l-.82-.94l-7.11-8.12l-.82-.94l.87-.9l7.01-7.2l.87-.9z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
