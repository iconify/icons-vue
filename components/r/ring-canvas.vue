<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5jbr8egz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ring-canvas" /></template>
<style>
.g5jbr8egz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25Q2.25 2.25 2.25 5q0 2.345 2 2.69v8.62q-2 .345-2 2.69q0 2.75 2.75 2.75q2.345 0 2.69-2h8.62q.345 2 2.69 2q2.75 0 2.75-2.75q0-2.345-2-2.69V7.69q2-.345 2-2.69q0-2.75-2.75-2.75q-2.345 0-2.69 2H7.69q-.345-2-2.69-2m2.69 3.5h8.62q.285 1.655 1.94 1.94v8.62q-1.655.285-1.94 1.94H7.69q-.285-1.655-1.94-1.94V7.69q1.655-.285 1.94-1.94m2.06 1.5h4.5q2.5 0 2.5 2.5v4.5q0 2.5-2.5 2.5h-4.5q-2.5 0-2.5-2.5v-4.5q0-2.5 2.5-2.5");
}

</style>
