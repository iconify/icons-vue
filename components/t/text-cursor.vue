<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr2zmbegu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:text-cursor" /></template>
<style>
.dr2zmbegu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.5q2.25 0 3 1.5q.75-1.5 3-1.5m-6 17q2.25 0 3-1.5q.75 1.5 3 1.5M12 5v14m-2-7h4");
}

</style>
