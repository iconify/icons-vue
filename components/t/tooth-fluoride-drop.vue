<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9cuchboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-fluoride-drop" /></template>
<style>
.v9cuchboa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 8.75c-2.5 0-3.25 1.5-3.25 3.5s1.25 3 1.75 4.5l1 4c.25 1 1.75 1 2 0l1-3.25c.25-1 3.25-1 3.5 0l1 3.25c.25 1 1.75 1 2 0l1-4c.5-1.5 1.75-2.5 1.75-4.5s-.75-3.5-3.25-3.5c-1.5 0-2.5 1.5-4.25 1.5s-2.75-1.5-4.25-1.5M12 2.25C11 3.5 10 4.5 10 5.5a2 2 0 0 0 4 0c0-1-1-2-2-3.25");
}

</style>
