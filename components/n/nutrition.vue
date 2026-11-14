<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u0gdaya4s"/><path class="x697gbcqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nutrition" /></template>
<style>
.u0gdaya4s {
  d: path("M12 7c-2-1.5-7.5-2-8 4c-.5 5 3 10 5.5 10c1.25 0 1.75-.75 2.5-.75s1.25.75 2.5.75c2.5 0 6-5 5.5-10c-.5-6-6-5.5-8-4Zm0 0l.75-4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x697gbcqz {
  d: path("M12 9.75c2.25 2 2.25 6 0 8c-2.25-2-2.25-6 0-8Zm0 2.75h.01M12 15h.01");
}

</style>
