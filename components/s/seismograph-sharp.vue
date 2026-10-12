<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ytqkenlip"/><path class="dvzhdg8hu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seismograph-sharp" /></template>
<style>
.dvzhdg8hu {
  d: path("M2.75 12h3L8 8.5l3 7l3-7l2.25 3.5h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ytqkenlip {
  d: path("M3.75 4.75h16.5v14.5H3.75z");
}

</style>
