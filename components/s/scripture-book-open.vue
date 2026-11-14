<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow15mziae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scripture-book-open" /></template>
<style>
.ow15mziae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6c-2-1.5-5.5-2-9-1.5V19c3.5-.5 7 0 9 1.5M12 6c2-1.5 5.5-2 9-1.5V19c-3.5-.5-7 0-9 1.5M12 6v14.5");
}

</style>
