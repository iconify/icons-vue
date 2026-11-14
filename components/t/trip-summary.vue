<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8vt0-9ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:trip-summary" /></template>
<style>
.m8vt0-9ws {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.757 4.25H6.5Q3.75 4.25 3.75 7v12q0 2.75 2.75 2.75h11q2.75 0 2.75-2.75V7q0-2.75-2.75-2.75h-1.262q-.078-.772-.647-1.341Q14.932 2.25 14 2.25h-.75q1.243 0 2.121.879q.879.878.879 2.121q0 1.948-1.265 2.631q.1.09.197.187Q16.5 9.386 16.5 11.25q0 3.311-3.97 7.28q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094Q7.5 14.561 7.5 11.25q0-1.864 1.318-3.182q.097-.097.197-.187Q7.75 7.198 7.75 5.25q0-1.243.879-2.121q.878-.879 2.121-.879H10q-2.121 0-2.243 2m5.493 2.5h-2.5q-1.5 0-1.5-1.5q0-.621.439-1.061q.44-.439 1.061-.439h2.5q.621 0 1.061.439q.439.44.439 1.061q0 1.5-1.5 1.5");
}

</style>
