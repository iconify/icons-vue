<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n2k6cws6i"/><path class="tzx9jpayz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-ream-sharp" /></template>
<style>
.n2k6cws6i {
  d: path("M6.75 3.25h10.5m-12.5 3h14.5m-16.5 3h18.5v12H2.75z");
}

.tzx9jpayz {
  d: path("M7.25 12.75h9.5v5h-9.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
