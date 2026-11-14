<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4a62q3lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:performance-rating" /></template>
<style>
.w4a62q3lc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4.25 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4.25 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4.25 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM19 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM3.5 12h.01m4.24 0h.01M12 12h.01");
}

</style>
