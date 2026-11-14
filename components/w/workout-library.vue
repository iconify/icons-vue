<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a28d_g84s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:workout-library" /></template>
<style>
.a28d_g84s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.511 14.218c2.009-.779 4.421-.811 6.989-.218V3.5c-3.25-.75-6.25-.5-8.5 1c-2.25-1.5-5.25-1.75-8.5-1V14c3.219-.743 6.193-.505 8.435.957M11 4.5v9.7m2.75 2.8h2.5v4.5h-2.5Zm5.5 0h2.5v4.5h-2.5Zm-3 2.25h3");
}

</style>
