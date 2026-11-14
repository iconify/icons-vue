<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_krs-dtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:switch-control" /></template>
<style>
.j_krs-dtn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 5.25h-8.5q-2.485 0-4.243 1.757Q1.75 8.765 1.75 11.25v1.5q0 2.485 1.757 4.243Q5.265 18.75 7.75 18.75h8.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-1.5q0-2.485-1.757-4.243Q18.735 5.25 16.25 5.25");
}

</style>
