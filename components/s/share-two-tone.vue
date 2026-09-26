<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ywvvvh6hi"/><path class="hezc43bmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:share-two-tone" /></template>
<style>
.hezc43bmb {
  d: path("M9.4551 9.9845L14.5449 7.0155M9.4551 14.0155L14.5449 16.9845M21 5C21 6.6569 19.6569 8 18 8C16.3431 8 15 6.6569 15 5C15 3.3431 16.3431 2 18 2C19.6569 2 21 3.3431 21 5ZM9 12C9 13.6569 7.6569 15 6 15C4.3431 15 3 13.6569 3 12C3 10.3431 4.3431 9 6 9C7.6569 9 9 10.3431 9 12ZM21 19C21 20.6569 19.6569 22 18 22C16.3431 22 15 20.6569 15 19C15 17.3431 16.3431 16 18 16C19.6569 16 21 17.3431 21 19Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ywvvvh6hi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 5C22 7.2092 20.2092 9 18 9C15.7908 9 14 7.2092 14 5C14 2.7908 15.7908 1 18 1C20.2092 1 22 2.7908 22 5ZM10 12C10 14.2092 8.2092 16 6 16C3.7908 16 2 14.2092 2 12C2 9.7908 3.7908 8 6 8C8.2092 8 10 9.7908 10 12ZM22 19C22 21.2092 20.2092 23 18 23C15.7908 23 14 21.2092 14 19C14 16.7908 15.7908 15 18 15C20.2092 15 22 16.7908 22 19Z");
  stroke: none;
}

</style>
