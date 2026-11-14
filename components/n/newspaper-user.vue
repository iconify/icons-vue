<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziamph52p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:newspaper-user" /></template>
<style>
.ziamph52p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 5.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M12 13c-2-1.5-5.5-2-9-1.5V20c3.5-.5 7 0 9 1.5c2-1.5 5.5-2 9-1.5v-8.5c-3.5-.5-7 0-9 1.5m0 0v8.5");
}

</style>
