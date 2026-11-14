<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwa9xzb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reflection-journal" /></template>
<style>
.nwa9xzb2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.7 18.5H4.5v-16h12v8.7m-14-4.7h4m-4 4.25h4M2.5 15h4m9.5 1.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm-2.5 5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

</style>
