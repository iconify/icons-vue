<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="wezofvl2u"/><path class="j5jpm4bzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tram-front-fill" /></template>
<style>
.j5jpm4bzx {
  d: path("M8 2L16 2M10 6L12 2L14 6M8 20L7 22M16 20L17 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wezofvl2u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 5L17 5C19.2092 5 21 6.7908 21 9L21 17C21 19.2092 19.2092 21 17 21L7 21C4.7908 21 3 19.2092 3 17L3 9C3 6.7908 4.7908 5 7 5ZM5 11L19 11L19 9C19 7.8954 18.1046 7 17 7L7 7C5.8954 7 5 7.8954 5 9L5 11ZM9 16C9 15.4477 8.5523 15 8 15C7.4477 15 7 15.4477 7 16C7 16.5523 7.4477 17 8 17C8.5523 17 9 16.5523 9 16ZM17 16C17 15.4477 16.5523 15 16 15C15.4477 15 15 15.4477 15 16C15 16.5523 15.4477 17 16 17C16.5523 17 17 16.5523 17 16Z");
  stroke: none;
}

</style>
