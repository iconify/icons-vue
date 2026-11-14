<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt8f47b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:phone-lock" /></template>
<style>
.tt8f47b0q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 2.75q1.743 0 2.225 1.807l.753 3.011l.007.035q.32 1.595-1.069 2.521l-.943.628q1.372 2.482 3.77 3.781l.633-.949q.926-1.389 2.521-1.069l.035.007l3 .75q1.818.485 1.818 2.228v3q0 2.75-2.75 2.75q-6.311 0-11.03-4.72Q2.75 11.811 2.75 5.5q0-2.75 2.75-2.75zm8.25 2.5h1.5V5q0-.75-.75-.75t-.75.75zm3 .338q1 .581 1 2.162v.5q0 2.5-2.5 2.5h-1.5q-2.5 0-2.5-2.5v-.5q0-1.581 1-2.162V5q0-2.25 2.25-2.25T19.75 5z");
}

</style>
