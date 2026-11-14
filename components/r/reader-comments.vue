<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j0vu13bvu"/><path class="bq6_oza6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reader-comments" /></template>
<style>
.bq6_oza6z {
  d: path("M7 7.5V5a2 2 0 0 1 2-2h10.5a2 2 0 0 1 2 2v6.5a2 2 0 0 1-2 2H16M6 11h6.5M6 14h4");
}

.j0vu13bvu {
  d: path("M2.5 9.5a2 2 0 0 1 2-2H14a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H8l-3.5 3v-3a2 2 0 0 1-2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
