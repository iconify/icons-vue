<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byp6kixiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:muscular-system" /></template>
<style>
.byp6kixiq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.436 19.5h-.186c-.5 0-1-.5-1-1L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L6 14l.5-2l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75h4c1.25 0 2.25.25 2.5 1.5l2 2.5c.25 1-.25 1.5-1.25 1.5c-.75 0-1-.25-1.25-.75L12 12l.5 2l.275 1.561M7.25 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 17.25h5.25c1.25 0 2.25-1 2-2.25l-.75-2m-6.5 2c0-2.5 3.25-3 4.5-.75m0-3.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
