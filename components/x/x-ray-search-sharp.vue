<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="hl5hrcbal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:x-ray-search-sharp" /></template>
<style>
.hl5hrcbal {
  d: path("M12 5.75v12.5M12 8L8.727 6.773L6.75 8.75M12 8l3.273-1.227L17.25 8.75M12 11.25l-3.273-1.227L6.75 12m5.25-.75l3.273-1.227L17.25 12M12 14.5l-2.904-.996L7.5 15.1m4.5-.6l2.904-.996L16.5 15.1");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
