<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bloni3_li"/><path class="up-mbpb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:visitor-log" /></template>
<style>
.bloni3_li {
  d: path("M12 6c-2-1.5-5.5-2-9.5-1.5V19c4-.5 7.5 0 9.5 1.5c2-1.5 5.5-2 9.5-1.5V4.5C17.5 4 14 4.5 12 6Zm0 0v14.5M5 9h4.5M5 12.5h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.up-mbpb8j {
  d: path("m14 17l2-1.25l4.25-7.25l-1.5-1l-4.5 7.25Z");
}

</style>
