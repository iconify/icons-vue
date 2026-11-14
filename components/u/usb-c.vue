<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_f8l8_ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:usb-c" /></template>
<style>
.u_f8l8_ui {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 5.75h-8.5q-2.485 0-4.243 1.757Q1.75 9.265 1.75 11.75v.5q0 2.485 1.757 4.243Q5.265 18.25 7.75 18.25h8.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-.5q0-2.485-1.757-4.243Q18.735 5.75 16.25 5.75m-7.75 4h7q2.25 0 2.25 2.25t-2.25 2.25h-7q-2.25 0-2.25-2.25T8.5 9.75");
}

</style>
