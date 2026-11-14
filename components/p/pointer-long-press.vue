<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqdmyxsvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pointer-long-press" /></template>
<style>
.wqdmyxsvb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 1.75q-3.75 0-3.75 3.75t3.75 3.75t3.75-3.75t-3.75-3.75M5.263 12.513q1.096-1.097 2.487-.474V8.5q0-2.25 2.25-2.25t2.25 2.25v2.536q.232-.036.5-.036q.775 0 1.25.301q.475-.301 1.25-.301t1.25.301Q16.975 11 17.75 11q2 0 2 2v3.5q0 5.75-5.25 5.75H13q-2.744 0-4.107-2.059l-3.979-4.972q-.054-.068-.091-.146q-.685-1.435.44-2.56");
}

</style>
