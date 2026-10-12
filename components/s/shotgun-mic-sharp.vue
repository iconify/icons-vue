<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eygq-omok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shotgun-mic-sharp" /></template>
<style>
.eygq-omok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h18.5v4.5H2.75zM6 8.5h2m2 0h2m2 0h2m-5.25 2.25h3.5l-.09 1l-.82 8.5l-.09 1h-2.5l-.09-1l-.82-8.5l-.09-1z");
}

</style>
