<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ieqvthb-d"/><path class="sieogvbxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tab-two-tone" /></template>
<style>
.ieqvthb-d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2H18C20.2092 2 22 3.791 22 6V18C22 20.209 20.2092 22 18 22H6C3.7909 22 2 20.209 2 18V6C2 3.791 3.7909 2 6 2H12ZM18 3H12V7C12 7.552 12.4477 8 13 8H21V6C21 4.343 19.6569 3 18 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sieogvbxy {
  d: path("M12 3V7C12 7.552 12.4477 8 13 8H21M6 3H18C19.6569 3 21 4.343 21 6V18C21 19.657 19.6569 21 18 21H6C4.3432 21 3 19.657 3 18V6C3 4.343 4.3432 3 6 3Z");
}

</style>
