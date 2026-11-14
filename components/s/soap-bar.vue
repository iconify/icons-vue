<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiyo-6b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soap-bar" /></template>
<style>
.aiyo-6b5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12.5h15A1.5 1.5 0 0 1 21 14v6a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 20v-6a1.5 1.5 0 0 1 1.5-1.5ZM5 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM10.75 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3.5 3.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7 16h4");
}

</style>
