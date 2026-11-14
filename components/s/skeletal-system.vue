<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mxcf23b0i"/><path class="j2_pzonji"/><path class="yepcsqbby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skeletal-system" /></template>
<style>
.j2_pzonji {
  d: path("M15.5 20.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm3-5.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.mxcf23b0i {
  d: path("M11.436 19.5h-.186c-.5 0-1-.5-1-1L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L6 14l.5-2l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75h4c1.25 0 2.25.25 2.5 1.5l2 2.5c.25 1-.25 1.5-1.25 1.5c-.75 0-1-.25-1.25-.75L12 12l.5 2l.397 2.25m-5.647-12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9 15.5l3.5-3.5m-5.5 3.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yepcsqbby {
  d: path("M19.75 16.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
