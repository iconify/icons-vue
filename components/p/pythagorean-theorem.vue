<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3en67lfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pythagorean-theorem" /></template>
<style>
.x3en67lfd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 9.306V17q0-2.25 2.25-2.25H7q2.25 0 2.25 2.25v1.5q0 2.25-2.25 2.25h9.008q1.558 0 2.107-1.458q.548-1.459-.625-2.485L6.982 7.613q-1.091-.956-2.412-.356q-1.32.599-1.32 2.049");
}

</style>
