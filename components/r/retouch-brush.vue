<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yknl0mbbn"/><path class="oivlc3btk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:retouch-brush" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oivlc3btk {
  d: path("m10.03 9.97l1.44-1.44q.53-.53 1.06 0l2.94 2.94q.53.53 0 1.06l-1.44 1.44q-.53.53-1.06 0l-2.94-2.94q-.53-.53 0-1.06M14 10l6.75-6.75m-14.5-.5Q6.64 5.61 9.5 6q-2.86.39-3.25 3.25Q5.86 6.39 3 6q2.86-.39 3.25-3.25");
}

.yknl0mbbn {
  d: path("m9.5 10.5l4 4l-2 2Q8 19 3.75 20.25Q5 16 7.5 12.5Z");
}

</style>
