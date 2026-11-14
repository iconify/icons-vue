<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgv2tzbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:overhead-cost" /></template>
<style>
.bgv2tzbwa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 3.25h5.75Q15 3.25 15 6q0 2.183-1.733 2.633Q13.5 9.2 13.5 10q0 .909-.301 1.518Q14.5 12.109 14.5 14q0 2.183-1.733 2.633Q13 17.2 13 18q0 2.75-2.75 2.75H4.5q-2.75 0-2.75-2.75q0-1.139.805-1.945q.429-.428.953-.629Q3.25 14.842 3.25 14q0-.909.301-1.518Q2.25 11.891 2.25 10q0-2.183 1.733-2.633Q3.75 6.8 3.75 6q0-2.75 2.75-2.75m14.518 14.232q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
