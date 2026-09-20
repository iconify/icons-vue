<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1haxbhzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:night-sight-max-outline-rounded" /></template>
<style>
.h1haxbhzb {
  fill: currentColor;
  d: path("M17.5 7.5H15q-.213 0-.356-.144t-.144-.357t.144-.356T15 6.5h2.5V4q0-.213.144-.356t.357-.144t.356.144T18.5 4v2.5H21q.213 0 .356.144t.144.357t-.144.356T21 7.5h-2.5V10q0 .213-.144.356t-.357.144t-.356-.144T17.5 10zm-6.5 12q1.696 0 3.08-.797t2.382-2.228q-3.477.011-5.72-2.113T8.5 9q0-.517.073-1.041t.239-1.074q-1.958.736-3.135 2.383T4.5 13q0 2.692 1.904 4.596T11 19.5m6.85-3.46q-.892 2.047-2.742 3.253Q13.257 20.5 11 20.5q-3.12 0-5.31-2.19T3.5 13q0-2.7 1.693-4.766T9.52 5.65q.165-.03.288.03q.122.062.19.172q.066.11.082.249q.015.14-.052.316q-.263.619-.395 1.265T9.5 9q0 2.708 1.896 4.604T16 15.5q.323 0 .616-.032q.294-.032.601-.082q.2-.036.344.016t.222.156q.078.103.106.226q.028.122-.039.256m-7.098-1.7");
}

</style>
