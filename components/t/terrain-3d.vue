<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="duma6gb_s"/><path class="groz8qehx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:terrain-3d" /></template>
<style>
.duma6gb_s {
  d: path("M3 14c1-4.5 3.5-6.5 5.75-3.75C10.5 4.5 15 2.5 17.25 9.5C19 9 20.5 11 21 14v3.5l-9 4l-9-4Z");
}

.groz8qehx {
  d: path("m3 14l9 4l9-4m-9 4v3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
