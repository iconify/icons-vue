<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvx9c5b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tennis-ball-machine" /></template>
<style>
.rvx9c5b5x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 5.25h4q1.76 0 3.005 1.245T14.25 9.5v4q0 1.76-1.245 3.005q-.301.301-.632.53q.377.544.377 1.465q0 2.25-2.25 2.25T8.25 18.5q0-.413.076-.75h-.697q.121.35.121.75q0 .932-.659 1.591T5.5 20.75q-2.25 0-2.25-2.25q0-.921.377-1.465q-.331-.229-.632-.53Q1.75 15.26 1.75 13.5v-4q0-1.76 1.245-3.005T6 5.25m13 .5q-3.25 0-3.25 3.25T19 12.25T22.25 9T19 5.75M4.5 11.5q0 1.75.875 2.625T8 15q3.5 0 3.5-3.5T8 8t-3.5 3.5");
}

</style>
