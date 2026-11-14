<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fds92ybre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scripture-book" /></template>
<style>
.fds92ybre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5c-2.5-2-6-2-9.5-1v13c3.5-1 7-1 9.5 1c2.5-2 6-2 9.5-1v-13c-3.5-1-7-1-9.5 1Zm0 0v13");
}

</style>
