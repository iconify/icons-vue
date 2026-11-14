<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sjqf7rb6k"/><path class="x9e461bik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:visitor-log" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sjqf7rb6k {
  d: path("M12 6c-2-1.5-5.5-2-9.5-1.5V19c4-.5 7.5 0 9.5 1.5c2-1.5 5.5-2 9.5-1.5V4.5C17.5 4 14 4.5 12 6m0 0v14.5M5 9h4.5M5 12.5h4.5");
}

.x9e461bik {
  d: path("m14.96 16.4l.727-.455a1.5 1.5 0 0 0 .499-.513l3.608-6.154A.955.955 0 0 0 19.5 8a.873.873 0 0 0-1.225.266l-3.846 6.196a1.5 1.5 0 0 0-.216.625l-.088.788a.548.548 0 0 0 .835.525");
}

</style>
