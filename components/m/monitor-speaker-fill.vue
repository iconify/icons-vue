<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="cmeu_0bvx"/><path class="sry7f1b6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-speaker-fill" /></template>
<style>
.cmeu_0bvx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 3L19 3C21.2092 3 23 4.7908 23 7L23 17C23 19.2092 21.2092 21 19 21L15 21C12.7908 21 11 19.2092 11 17L11 7C11 4.7908 12.7908 3 15 3ZM19 15C19 13.8954 18.1046 13 17 13C15.8954 13 15 13.8954 15 15C15 16.1046 15.8954 17 17 17C18.1046 17 19 16.1046 19 15ZM18 8C18 7.4477 17.5523 7 17 7C16.4477 7 16 7.4477 16 8C16 8.5523 16.4477 9 17 9C17.5523 9 18 8.5523 18 8Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sry7f1b6v {
  d: path("M8 4L5 4C3.3431 4 2 5.3431 2 7L2 13C2 14.6569 3.3431 16 5 16L8 16M8 20L6 20");
}

</style>
