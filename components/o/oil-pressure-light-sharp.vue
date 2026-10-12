<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sfbqf765l"/><path class="efon4kbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oil-pressure-light-sharp" /></template>
<style>
.efon4kbes {
  d: path("M5 16.25a2.5 2.5 0 0 1 5 0m-2.5 0L9 14.5m11-1.25l1.25 1.618v.882a1.25 1.25 0 0 1-2.5 0v-.882z");
}

.sfbqf765l {
  d: path("M4.25 11H11l.93.83l.39.34l.93.83l.96-.8l3.83-3.15l.96-.8l-.44 1.17l-3.12 8.16l-.44 1.17H3V11zM7 11V8.75m-2 0h4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
