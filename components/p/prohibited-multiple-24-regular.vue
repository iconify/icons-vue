<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c38hy-b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-multiple-24-regular" /></template>
<style>
.c38hy-b3m {
  fill: currentColor;
  d: path("M5.697 5.697a7.5 7.5 0 0 1 10.05-.504L5.193 15.747a7.5 7.5 0 0 1 .504-10.05m.556 11.11L16.807 6.253A7.5 7.5 0 0 1 6.253 16.807M17.364 4.636A9 9 0 1 0 4.636 17.364A9 9 0 0 0 17.364 4.636M21 11c0 5.523-4.477 10-10 10c-.864 0-1.702-.11-2.501-.315A9 9 0 0 0 20.685 8.499c.206.8.315 1.637.315 2.501");
}

</style>
