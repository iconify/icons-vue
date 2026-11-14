<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k993-msbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:microcentrifuge" /></template>
<style>
.k993-msbl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M6 8.25Q6 6 8.25 6t2.25 2.25t-2.25 2.25T6 8.25M15.75 6Q18 6 18 8.25t-2.25 2.25t-2.25-2.25T15.75 6m-7.5 7.5q2.25 0 2.25 2.25T8.25 18T6 15.75t2.25-2.25m5.25 2.25q0-2.25 2.25-2.25T18 15.75T15.75 18t-2.25-2.25M10 12q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
