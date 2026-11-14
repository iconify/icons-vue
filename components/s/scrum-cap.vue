<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t678k01mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scrum-cap" /></template>
<style>
.t678k01mj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 17.5V12a8 8 0 0 1 16 0v5.5h-4V14a4 4 0 0 0-8 0v3.5Zm2 0q6 6 12 0M12 4v3.25");
}

</style>
