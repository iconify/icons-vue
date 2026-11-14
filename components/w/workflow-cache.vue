<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cheggdeqz"/><path class="yxvppjbfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:workflow-cache" /></template>
<style>
.cheggdeqz {
  d: path("M2.5 11.5H9V18H2.5Zm10.5-9h6.5V9H13Zm-7.25 9V5.75H13m2 10a3.25 1.5 0 1 0 6.5 0a3.25 1.5 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yxvppjbfk {
  d: path("M15 15.75V20a3.25 1.5 0 0 0 6.5 0v-4.25");
}

</style>
