<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zitu0ab1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:metronome-device" /></template>
<style>
.zitu0ab1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.076 2.5h1.848a2.625 2.625 0 0 1 2.554 2.02l3.257 13.75a2.625 2.625 0 0 1-2.554 3.23H7.819a2.625 2.625 0 0 1-2.554-3.23L8.522 4.52a2.625 2.625 0 0 1 2.554-2.02M5.75 17h12.5M12 17l3-10");
}

</style>
