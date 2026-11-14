<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx46z9gtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:significant-figures" /></template>
<style>
.rx46z9gtr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.5H7l-2 4a3 3 0 1 1-2.25 5M12.5 10l1.75-1.5v10M21 8.5h-3.5l-.25 4.25h1.25a2.75 2.75 0 0 1 0 5.5H17m-7 .25h.01M19.25 5h.01");
}

</style>
