<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2zyfvkev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:medal-ribbon-sport" /></template>
<style>
.q2zyfvkev {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.48 2.25H17.5q.193 0 .362.093q.131.072.224.189t.135.26q.028.097.029.198V3q0 .193-.093.362l-.001.001l-3.55 6.435q.984.454 1.813 1.283q1.831 1.83 1.831 4.419t-1.831 4.419T12 21.75t-4.419-1.831Q5.75 18.089 5.75 15.5t1.831-4.419q.829-.829 1.813-1.283L5.843 3.362q-.091-.165-.093-.353V3q0-.106.029-.208q.042-.143.135-.26t.224-.189q.159-.088.342-.093m1.29 1.5l3.087 5.595Q11.409 9.25 12 9.25t1.143.095L16.23 3.75z");
}

</style>
