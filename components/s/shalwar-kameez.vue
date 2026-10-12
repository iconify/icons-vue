<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nyh7znbmh"/><path class="lh7cwvb8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shalwar-kameez" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lh7cwvb8r {
  d: path("M9.75 3L12 5.25L14.25 3M8.5 15.5h7q.5 0 .59.49l.82 4.77q.09.49-.41.49h-2.75q-.5 0-.67-.47l-.91-2.56q-.17-.47-.34 0l-.91 2.56q-.17.47-.67.47H7.5q-.5 0-.41-.49l.82-4.77q.09-.49.59-.49");
}

.nyh7znbmh {
  d: path("M9.75 2.75h4.5q.75 0 1.4.37l2.7 1.51q.65.37.86 1.09l1.33 4.56q.21.72-.52.88l-.79.18q-.73.16-1.1-.49l-1.26-2.2q-.37-.65-.37.1v6q0 .75-.75.75h-7.5q-.75 0-.75-.75v-6q0-.75-.37-.1l-1.26 2.2q-.37.65-1.1.49l-.79-.18q-.73-.16-.52-.88l1.33-4.56Q5 5 5.65 4.63l2.7-1.51q.65-.37 1.4-.37");
}

</style>
