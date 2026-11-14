<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srpilk0yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tealight" /></template>
<style>
.srpilk0yv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.611 8.641q-1.423-.864-1.448-2.448q-.024-1.461 1.237-3.143q.09-.119.218-.195t.276-.097t.292.015t.264.127q.086.064.15.15q1.261 1.682 1.237 3.143q-.025 1.584-1.448 2.448q-.088.054-.187.081T12 8.75q-.103 0-.202-.028q-.099-.027-.187-.081M4.25 12.999Q4.252 10 12 10q7.75 0 7.75 3v3.75q0 3.75-7.75 3.75t-7.75-3.75zm1.5 2.06v1.691Q5.75 19 12 19t6.25-2.25v-1.691Q16.34 16 12 16t-6.25-.941");
}

</style>
