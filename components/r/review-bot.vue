<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ehew8or0e"/><path class="dcn6aopcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:review-bot" /></template>
<style>
.dcn6aopcd {
  d: path("M16.5 2.5h3a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2.25L15 10V4a1.5 1.5 0 0 1 1.5-1.5Z");
}

.ehew8or0e {
  d: path("M17.5 11.686V20.5q0 .098-.019.195t-.057.188t-.093.173q-.054.081-.124.151t-.151.124q-.082.055-.173.093t-.188.057t-.195.019h-13q-.098 0-.195-.019t-.188-.057t-.173-.093t-.151-.124t-.124-.151t-.093-.173t-.057-.188T2.5 20.5V8q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T3.5 7h8.7m-5.7 5.5V15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
