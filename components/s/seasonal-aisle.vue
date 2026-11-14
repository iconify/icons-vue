<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="phqe6-ptf"/><path class="txacaxx6e"/><path class="rx5vjdb4t"/><path class="lr8fz0b5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seasonal-aisle" /></template>
<style>
.lr8fz0b5p {
  d: path("M12 5q2.5-2.5 5.5-1.5Q15.5 6 12 5Z");
}

.phqe6-ptf {
  d: path("M2.5 14a9.5 7 0 1 0 19 0a9.5 7 0 1 0-19 0Z");
}

.rx5vjdb4t {
  d: path("M12 7V4.5q0-1.5 1-2");
}

.txacaxx6e {
  d: path("M8.5 14a3.5 7 0 1 0 7 0a3.5 7 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
