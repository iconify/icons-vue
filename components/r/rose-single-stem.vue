<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dad3i6b9n"/><path class="q5o07jbzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rose-single-stem" /></template>
<style>
.dad3i6b9n {
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.q5o07jbzl {
  d: path("M12 5.25A2.25 2.25 0 1 1 9.75 7.5m2.25 5v9m0-2c0-2.5-2-4-5-4c0 2.5 2 4 5 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
