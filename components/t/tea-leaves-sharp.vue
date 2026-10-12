<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y1o7v_6vk"/><path class="pza7i-jar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tea-leaves-sharp" /></template>
<style>
.pza7i-jar {
  d: path("M12 13q4-5.12 0-10.25Q8 7.88 12 13Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1o7v_6vk {
  d: path("M12 21.25V14m0 1q-1.31-7.89-9.25-7q1.31 7.89 9.25 7Zm0 0q7.94.89 9.25-7q-7.94-.89-9.25 7Zm-1.5-1.25L6 10.5m7.5 3.25L18 10.5");
}

</style>
