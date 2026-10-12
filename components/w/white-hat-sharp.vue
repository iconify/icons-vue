<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kbpiokbqt"/><path class="rk7rft3-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:white-hat-sharp" /></template>
<style>
.kbpiokbqt {
  d: path("M2.75 11.75v-1.189l3.5-.461V6.75c0-2.2 2.3-4 5.75-4s5.75 1.8 5.75 4v3.35c1.9.25 3.5.85 3.5 1.65c0 1.1-4.15 2-9.25 2s-9.25-.9-9.25-2Z");
}

.rk7rft3-j {
  d: path("M6.25 8.25C10 9 14 9 17.75 8.25M8.5 18.5L11 21l4.75-4.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
