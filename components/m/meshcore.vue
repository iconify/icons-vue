<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ps4xiqbrp"/><path class="fs95zr-oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meshcore" /></template>
<style>
.fs95zr-oz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.236 31.248c-1.804-1.88-2.88-4.443-2.88-7.248s1.076-5.368 2.88-7.248M9.747 37.298C6.486 33.811 4.5 29.14 4.5 24s1.986-9.81 5.246-13.298m22.018 6.05c1.804 1.88 2.88 4.443 2.88 7.248s-1.076 5.368-2.88 7.248m6.49-20.546C41.514 14.189 43.5 18.86 43.5 24s-1.986 9.81-5.246 13.298");
}

.ps4xiqbrp {
  cx: 24px;
  cy: 24px;
  r: 3.651px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
