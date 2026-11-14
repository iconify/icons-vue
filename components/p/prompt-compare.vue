<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1nuid9nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prompt-compare" /></template>
<style>
.u1nuid9nz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8h2.75a2 2 0 0 1 2 2v1.5a2 2 0 0 1-2 2H6.5l-2 3v-3a2 2 0 0 1-2-2V10a2 2 0 0 1 2-2m12.25 0h2.75a2 2 0 0 1 2 2v1.5a2 2 0 0 1-2 2v3l-2-3h-.75a2 2 0 0 1-2-2V10a2 2 0 0 1 2-2M12 3.5v17");
}

</style>
