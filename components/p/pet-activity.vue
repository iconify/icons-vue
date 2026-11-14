<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1d61ib8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-activity" /></template>
<style>
.c1d61ib8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h19m-17.75 0V18h3.5v3.5m2.75 0v-6.25h3.5v6.25m3 0v-8.75H20v8.75M15.75 8.25a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0ZM15.5 4.5h.01M18.25 3h.01M21 4.5h.01");
}

</style>
