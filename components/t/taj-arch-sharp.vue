<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vk0dgqj9c"/><path class="wr12ielji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:taj-arch-sharp" /></template>
<style>
.vk0dgqj9c {
  d: path("M12 5.75c3 1.5 5 3.5 5 6v1.417l-.75.833h-8.5L7 13.167V11.75c0-2.5 2-4.5 5-6Zm0-3v3M2.75 9.5v11.75M21.25 9.5v11.75M5.75 14h12.5v7.25H5.75z");
}

.wr12ielji {
  d: path("M10 21.25V16.5h4v4.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
