<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzjutd8ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:unit-cell" /></template>
<style>
.xzjutd8ca {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25Q2.25 2.25 2.25 5q0 2.345 2 2.69v8.62q-2 .345-2 2.69q0 2.75 2.75 2.75q2.345 0 2.69-2h8.62q.345 2 2.69 2q2.75 0 2.75-2.75q0-2.345-2-2.69V7.69q2-.345 2-2.69q0-2.75-2.75-2.75q-2.345 0-2.69 2H7.69q-.345-2-2.69-2m13.25 14.06q-1.655.285-1.94 1.94H7.69q-.285-1.655-1.94-1.94V7.69q1.655-.285 1.94-1.94h8.62q.285 1.655 1.94 1.94zM8.75 12q0-3.25 3.25-3.25T15.25 12T12 15.25T8.75 12");
}

</style>
