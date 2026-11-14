<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhhxssbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:microbe-plate-colonies" /></template>
<style>
.nhhxssbef {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M15 6.75q2 0 2 2t-2 2t-2-2t2-2M5.75 10q0-2.75 2.75-2.75T11.25 10T8.5 12.75T5.75 10m5.5 5.5q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T13.75 18q-2.5 0-2.5-2.5");
}

</style>
