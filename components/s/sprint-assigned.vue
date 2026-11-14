<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-4jhsovo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sprint-assigned" /></template>
<style>
.s-4jhsovo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.558 5.517l-4.013 4.957A1.55 1.55 0 0 0 5.75 13h1.04a1.75 1.75 0 0 1 1.704 2.151L8 17.25a.765.765 0 0 0 1.385.593l3.613-5.54A1.49 1.49 0 0 0 11.75 10h-.472a1.75 1.75 0 0 1-1.691-2.201L10 6.25a.827.827 0 0 0-1.442-.733M14.5 21.25c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5c0 .25-.25.5-.5.5h-6c-.25 0-.5-.25-.5-.5m1.75-6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
