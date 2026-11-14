<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci76iqb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:org-chart-horizontal" /></template>
<style>
.ci76iqb6x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.299 6.25H13.5q-.75 0-.75.75v10q0 .75.75.75h1.799q.351-2.5 3.201-2.5q1.346 0 2.298.952t.952 2.298t-.952 2.298t-2.298.952q-2.85 0-3.201-2.5H13.5q-2.25 0-2.25-2.25v-4.25H8.701q-.351 2.5-3.201 2.5q-3.25 0-3.25-3.25T5.5 8.75q2.85 0 3.201 2.5h2.549V7q0-2.25 2.25-2.25h1.799q.351-2.5 3.201-2.5q1.346 0 2.298.952T21.75 5.5t-.952 2.298t-2.298.952q-2.85 0-3.201-2.5");
}

</style>
