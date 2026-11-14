<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="np79jabog"/><path class="r32ed_b0e"/><path class="goyk9e4gg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sim-card-dual" /></template>
<style>
.goyk9e4gg {
  d: path("M11 11.5h6V18h-6Z");
}

.np79jabog {
  d: path("M10 5.5h6l4 4v10a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2v-12a2 2 0 0 1 2-2Z");
}

.r32ed_b0e {
  d: path("M8 18.5H6a2 2 0 0 1-2-2v-12a2 2 0 0 1 2-2h6l3 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
