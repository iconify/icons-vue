<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1cc3ol4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pipeline-leak" /></template>
<style>
.w1cc3ol4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5H14m3 0h4.5m-19 5H8L9 13l1-1.5h4m3 0h4.5m-6.3 2H14v-9h3v7.2m-8 4.05l1.75 3a2 2 0 1 1-3.5 0Zm9-1.25V18m0 3h.01");
}

</style>
