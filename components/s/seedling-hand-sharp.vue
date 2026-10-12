<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iulni1bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seedling-hand-sharp" /></template>
<style>
.iulni1bdf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25v7.5m3-6.5h2.5l2.1-1.1l.443-.245l.507-.005h3.95v3H11.5m-5.75 4.35h6.6l1.037-.005l.813-.645l5.6-4.4l1.099-1.014l-1.85-2.35l-1.099 1.014l-3.2 2.5m-1.5-4.6V7m0 0C13 4.5 11.5 3.25 9 3.25C9.25 5.75 10.75 7 13.25 7Zm0 0C13.5 4.5 15 3.25 17.5 3.25C17.25 5.75 15.75 7 13.25 7Z");
}

</style>
