<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="asg51hbqf"/><path class="wjfks33vt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-full-duotone" /></template>
<style>
.asg51hbqf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 5a1 1 0 0 1 1 1v13a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3V6a1 1 0 0 1 1-1Zm-9 5v7a1 1 0 0 0 2 0v-7a1 1 0 0 0-2 0m4 0v7a1 1 0 0 0 2 0v-7a1 1 0 0 0-2 0");
}

.ft5dv1b6b {
  fill: none;
}

.wjfks33vt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6v13a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V6M4 6h16M8 6V5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v1m-6 4v7m4-7v7");
}

</style>
