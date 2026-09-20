<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdisqhexm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:step-over-rounded" /></template>
<style>
.wdisqhexm {
  fill: currentColor;
  d: path("M10.23 17.772q-.73-.729-.73-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731t-1.771-.728M17.45 10.5q-.723-1.561-2.172-2.53Q13.828 7 12 7q-1.918 0-3.438 1.095t-2.168 2.81q-.075.236-.233.415q-.157.18-.386.18q-.242 0-.373-.19q-.13-.189-.063-.402Q6 8.762 7.805 7.38T11.975 6q1.864 0 3.394.891q1.531.892 2.458 2.34V6.385q0-.213.144-.357q.144-.143.356-.143q.213 0 .357.143t.143.357v4.307q0 .344-.232.576t-.576.232h-4.307q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143z");
}

</style>
