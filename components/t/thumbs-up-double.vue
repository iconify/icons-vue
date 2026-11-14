<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz0c-_6hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thumbs-up-double" /></template>
<style>
.dz0c-_6hb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12.5h2.5l2.5-5c.75-1.25 2.75-1 2.75.75v3.25h2.75a1.75 1.75 0 0 1 1.75 2l-.75 6a2 2 0 0 1-2 2H9Zm2.5 0v9m-8.5-4v-9h3.5l2.5-5c.5-1.25 2.5-1 2.75.5");
}

</style>
