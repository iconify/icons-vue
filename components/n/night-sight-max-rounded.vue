<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwdjqtbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:night-sight-max-rounded" /></template>
<style>
.dwdjqtbwb {
  fill: currentColor;
  d: path("M17.5 7.5H15q-.213 0-.356-.144t-.144-.357t.144-.356T15 6.5h2.5V4q0-.213.144-.356t.357-.144t.356.144T18.5 4v2.5H21q.213 0 .356.144t.144.357t-.144.356T21 7.5h-2.5V10q0 .213-.144.356t-.357.144t-.356-.144T17.5 10zm.35 8.54q-.892 2.047-2.742 3.253Q13.257 20.5 11 20.5q-3.12 0-5.31-2.19T3.5 13q0-2.7 1.693-4.766T9.52 5.65q.165-.03.288.03q.122.062.19.172q.066.11.082.249q.015.14-.052.316q-.263.619-.395 1.265T9.5 9q0 2.708 1.896 4.604T16 15.5q.323 0 .616-.032q.294-.032.601-.082q.2-.036.344.016t.222.156q.078.103.106.226q.028.122-.039.256");
}

</style>
