<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg53u3q9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:particles-vfx" /></template>
<style>
.hg53u3q9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.5q1 6 7 7q-6 1-7 7q-1-6-7-7q6-1 7-7Zm8-3.5q.5 2.5 3 3q-2.5.5-3 3q-.5-2.5-3-3q2.5-.5 3-3Zm1 13q.5 2 2.5 2.5q-2 .5-2.5 2.5q-.5-2-2.5-2.5q2-.5 2.5-2.5Z");
}

</style>
