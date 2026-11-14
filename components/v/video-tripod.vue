<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbzs0jblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:video-tripod" /></template>
<style>
.nbzs0jblz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 5h5.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 14.75 9h-5.5A1.75 1.75 0 0 1 7.5 7.25v-.5A1.75 1.75 0 0 1 9.25 5M7.5 7l-5 2.5M12 9v12m0-9.5L5.5 21m6.5-9.5l6.5 9.5");
}

</style>
