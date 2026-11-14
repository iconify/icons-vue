<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcmmdvbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:slicer-buttons" /></template>
<style>
.dcmmdvbyd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 4.25H5q-1.346 0-2.298.952T1.75 7.5q0 3.25 3.25 3.25h3.5q3.25 0 3.25-3.25T8.5 4.25m7 0H19q1.346 0 2.298.952T22.25 7.5q0 3.25-3.25 3.25h-3.5q-3.25 0-3.25-3.25t3.25-3.25m-7 9H5q-1.346 0-2.298.952T1.75 16.5q0 3.25 3.25 3.25h3.5q3.25 0 3.25-3.25T8.5 13.25m7 0H19q1.346 0 2.298.952t.952 2.298q0 3.25-3.25 3.25h-3.5q-3.25 0-3.25-3.25t3.25-3.25");
}

</style>
