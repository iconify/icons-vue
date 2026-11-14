<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gxi98dbew"/><path class="uxlzlqbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:short-video-effects" /></template>
<style>
.gxi98dbew {
  d: path("M3 7.5h11.5v14H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uxlzlqbfb {
  d: path("m7 11.5l4 3l-4 3ZM18.25 2q0 3.5 3.5 3.5q-3.5 0-3.5 3.5q0-3.5-3.5-3.5q3.5 0 3.5-3.5Z");
}

</style>
