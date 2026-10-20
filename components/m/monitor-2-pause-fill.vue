<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="eux4g80uq"/><path class="jwuruxbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-pause-fill" /></template>
<style>
.eux4g80uq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2L19 2C21.2092 2 23 3.7908 23 6L23 14C23 16.2092 21.2092 18 19 18L5 18C2.7908 18 1 16.2092 1 14L1 6C1 3.7908 2.7908 2 5 2ZM11 7C11 6.4477 10.5523 6 10 6C9.4477 6 9 6.4477 9 7L9 13C9 13.5523 9.4477 14 10 14C10.5523 14 11 13.5523 11 13L11 7ZM15 7C15 6.4477 14.5523 6 14 6C13.4477 6 13 6.4477 13 7L13 13C13 13.5523 13.4477 14 14 14C14.5523 14 15 13.5523 15 13L15 7Z");
  stroke: none;
}

.jwuruxbqn {
  d: path("M12 17L12 21M8 21L16 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
