<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyzgtxb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snowflake" /></template>
<style>
.wyzgtxb0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m-2.5-17L12 7l2.5-2.5m-5 15L12 17l2.5 2.5m5.727-12.25l-16.454 9.5M17.245 6.085L16.33 9.5l3.415.915m-15.49 3.17l3.415.915l-.915 3.415m13.472-1.165L3.773 7.25m15.972 6.335l-3.415.915l.915 3.415M6.755 6.085L7.67 9.5l-3.415.915");
}

</style>
