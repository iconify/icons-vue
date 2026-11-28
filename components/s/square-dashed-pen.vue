<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg9mhub6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-dashed-pen" /></template>
<style>
.jg9mhub6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6C3 4.34315 4.34315 3 6 3M10.5 3H12.5M21 11.5V13.5M21 18C21 19.6569 19.6569 21 18 21M13.5 21H10.5M6 21C4.34315 21 3 19.6569 3 18M3 13.5V10.5M10.5 13.5L14.6248 11.8501L20.4874 5.9874C21.1709 5.304 21.1709 4.196 20.4874 3.5126C19.804 2.8291 18.696 2.8291 18.0126 3.5126L12.1499 9.3752Z");
}

</style>
