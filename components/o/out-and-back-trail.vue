<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o7k9f5qkf"/><path class="db2gipbug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:out-and-back-trail" /></template>
<style>
.db2gipbug {
  d: path("M10.75 13.5L8.25 16l2.5 2.5");
}

.o7k9f5qkf {
  d: path("M3.25 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0h9.5a4 4 0 0 1 0 8h-8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
