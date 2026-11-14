<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9rcjuxqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:quiz-timer" /></template>
<style>
.x9rcjuxqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13.5a7.75 7.75 0 1 0 15.5 0a7.75 7.75 0 1 0-15.5 0ZM10 2.5h4m-2 11v-4m0 4l3 1.5M12 2.5v3.25");
}

</style>
