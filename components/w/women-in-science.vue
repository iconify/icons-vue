<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytsyu3k7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:women-in-science" /></template>
<style>
.ytsyu3k7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 7.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM2.5 20c0-3.5 3-5.75 6.5-5.75c1.969 0 3.78.712 4.988 1.959M14.5 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm3.5 5.25c1.519 0 2.661.377 3.263.966M16.75 14.5V17l-2.25 4.5h7L19.25 17v-2.5");
}

</style>
