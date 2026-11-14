<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x25s5gn8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sparkler-cross" /></template>
<style>
.x25s5gn8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 21l9.5-13M19 21L9.5 8M12 5h.01M12 2.25v.5M8.75 4l.5.25m6-.25l-.5.25");
}

</style>
