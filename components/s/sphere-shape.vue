<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwugbmu2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sphere-shape" /></template>
<style>
.qwugbmu2y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M22.25 12q0 1.973-3.273 3.179Q16.069 16.25 12 16.25t-6.977-1.071Q1.75 13.973 1.75 12t3.273-3.179Q7.931 7.75 12 7.75t6.977 1.071Q22.25 10.027 22.25 12M5.542 13.771Q3.25 12.927 3.25 12t2.292-1.771Q8.199 9.25 12 9.25t6.458.979q2.292.844 2.292 1.771t-2.292 1.771q-2.657.979-6.458.979t-6.458-.979");
}

</style>
